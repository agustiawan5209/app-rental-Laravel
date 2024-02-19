<template>
    <Bar id="my-chart-id" :options="chartOptions" :data="chartData" />
</template>

<script>
import { Bar } from 'vue-chartjs'
import { Chart as ChartJS, Title, Tooltip, Legend, BarElement, CategoryScale, LinearScale } from 'chart.js'

ChartJS.register(Title, Tooltip, Legend, BarElement, CategoryScale, LinearScale)

export default {
    name: 'BarChart',
    components: { Bar },
    props: { dataSewa: Object },
    data() {
        return {
            chartData: {
                // labels: [
                //     'January',
                //     'February',
                //     'March',
                //     'April',
                //     'May',
                //     'June',
                //     'July',
                //     'August',
                //     'September',
                //     'October',
                //     'November',
                //     'December'
                // ],
                datasets: [
                    {
                        label: 'Data Pendapatan per Bulan ',
                        backgroundColor: '#f87979',
                        data: this.dataSewa
                    }
                ],
                backgroundColor: '#f87979',
            },
            chartOptions: {
                responsive: true
            }
        }
    }
}
</script>
