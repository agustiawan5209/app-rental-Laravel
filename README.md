

---

## Website Sistem Informasi Rental 🚗  

Sistem informasi rental kendaraan untuk pengelolaan data kendaraan, pelacakan kendaraan, dan pengelolaan transaksi. Dibangun menggunakan **Laravel, Vue.js, dan Inertia.js**.  

### 🚀 Fitur Utama  
- **Manajemen Kendaraan**: Tambah, edit, dan hapus data kendaraan.  
- **Pelacakan Kendaraan**: Monitoring kendaraan yang sedang disewa.  
- **Manajemen Transaksi**: Catatan transaksi penyewaan kendaraan.  
- **Autentikasi & Hak Akses**: Login, registrasi, dan peran pengguna.  

### 🛠️ Teknologi yang Digunakan  
- **Backend**: Laravel  
- **Frontend**: Vue.js dengan Inertia.js  
- **Database**: MySQL / PostgreSQL  
- **Lainnya**: Tailwind CSS  

### ⚙️ Cara Instalasi  

1. **Clone repository ini**  
   ```sh
   git clone (https://github.com/agustiawan5209/app-rental-Laravel)
   cd repository
   ```

2. **Instal dependensi backend**  
   ```sh
   composer install
   cp .env.example .env
   php artisan key:generate
   ```

3. **Instal dependensi frontend**  
   ```sh
   npm install
   npm run dev
   ```

4. **Migrasi database**  
   ```sh
   php artisan migrate --seed
   ```

5. **Jalankan server**  
   ```sh
   php artisan serve
   ```

6. **Akses aplikasi**  
   Buka browser dan masuk ke `http://localhost:8000`.  

### 📜 Lisensi  
Proyek ini menggunakan lisensi **MIT**.  

---

Apakah ada bagian yang ingin Anda tambahkan atau ubah? 😊
