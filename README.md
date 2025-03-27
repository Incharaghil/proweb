## Kontributor  
### Tiya Mitra Ayu 10231088 (@Tiyamitraayu) – Backend  
### Incha Raghil 10231088 (@Incharaghil) – Frontend 

# Pemrograman Web

# 💰 Sistem Manajemen E-commerce Sederhana

## Link Repostiory : https://github.com/incharaghil/proweb

## 📝 Deskripsi Aplikasi 
Sistem Manajemen E-Commerce Sederhana adalah sebuah platform yang digunakan untuk mengelola toko online secara efisien. Sistem ini memiliki fitur utama seperti menambahkan, mengedit, dan menghapus produk, sehingga memudahkan pengguna dalam mengatur katalog barang yang dijual. Selain itu, dapat dilengkapi dengan manajemen pesanan, data pelanggan, dan laporan penjualan untuk mendukung operasional bisnis secara lebih terstruktur. 

## 🛠️ Setup & Panduan Pengguna 
### 1. Kebutuhan Pembuatan Sistem
Sebelum memulai perangkat perlu menyediakan spesifikasi tools yaitu

✅ **Node.js** versi 14

✅ **MySQL** minimal 8.0

✅ **NPM** versi 6

### 2. Teknologi yang Digunakan

#### 🎨**Frontend (React.js + TypeScript)**
-  **Vite** digunakan sebagai build tool untuk pengembangan yang lebih cepat.
-  **TypeScript** membantu menjaga keamanan tipe data.
-  **React Hooks** mengelola state aplikasi secara efisien.
-  **React** digunakan untuk komunikasi dengan backend, lengkap dengan penanganan error.
-  **CSS Modern** diterapkan dengan **Flexbox**, desain responsif, serta animasi dan transisi.

#### ⚙️ **Backend (Node.js + Express.js)**
- **Express.js** digunakan untuk membangun **RESTful API.**
- Middleware dipakai untuk menangani **CORS** dan error handling.
- **MySQL** sebagai database relasional dengan query yang dioptimalkan.

### 3. Langkah Instalasi & Konfigurasi
- **Clone Repository**
  Repository disalin ke dalam perangkat lokal dengan perintah berikut:
  ```
  git clone [URL_REPOSITORY]
  cd proweb
  ```
- **Setup Database**
    1. Buat database baru di **pgAdmin 4**
    2. Impor struktur database
    3. Menyesuaikan kebutuhan data untuk backend
- **Instalasi Dependensi**

  ➡️**Frontend**
  ```
  cd proweb-frontend
  npm install
  ```
  ➡️**Backend**
  ```
  cd proweb-backend
  npm install
  ```
- **Konfigurasi Environment**
  Menyesuaikan file yang dibuat untuk backend
  1. Buat file di dalam folder backend
  2. Tambahkan kofigurasi sesuai dengan database yang digunakan
     ```
     DB_HOST=localhost
     DB_USER=your_username
     DB_PASSWORD=your_password
     DB_NAME=your_database
     PORT=3001

### 4. Manjalankan Aplikasi
- **Menjalankan backend**
  Untuk menjalankan Backend, menggunakan kode yang dijalankan pada terminal yaitu
  ```
  cd proweb-backend
  npm start
  ```
- **Menjalankan Frontend**
  Untuk menjalankan Backend, menggunakan kode yang dijalankan pada terminal yaitu
  ```
  cd proweb-frontend
  npm run dev
  ```
### 5. Instruksi Instalansi
1. **Clone Repository**
    Menyalin repository ke perangkat lokal dengan kode dibawah
    ```
    git clone [URL_REPOSITORY]
    cd proweb
    ```
2. **Setup Database (PostgreSQL-pgAdmin 4)**
3. **Install Dependencies untuk Frontend**
   ```
   cd proweb-frontend
   npm install
   ```
4. **Konfigurasi Environment**
   - Membuat file .env di dalam folder backend
   - Mengisi dengan konfigurasi PostgreSQL
     ```
     DB_HOST=localhost
     DB_USER=your_username
     DB_PASSWORD=your_password
     DB_NAME=your_database
     DB_PORT=5432  # Port default PostgreSQL
     PORT=3001  # Port backend
     ```
6. **Jalankan Backend**
   Untuk menjalankan backend perlu dilakukan dengan penggunakan perintah
   ```
   cd proweb-backend
   npm start
   ```
8. **Jalankan Frontend**
   ```
   cd proweb-frontend
   npm run dev
   ```
### 6. Instruksi Instalansi
```
proweb/
├── proweb-frontend/
│   ├── src/
│   │   ├── components/
│   │   │   └── ProdukList.tsx    
│   │   ├── App.tsx              
│   │   └── App.css              
│   ├── public/                  
│   └── package.json            
└── proweb-backend/
    ├── index.js                
    ├── db.js                  
    └── package.json           
```

### 7. API Endpoints
#### Produk
- GET/produk
  
  📌 Deskripsi: Mendapatkan semua produk

  📤 Response: Array of products
  
  ✅ Status: 200 OK
  
- POST/produk
  
  📌 Deskripsi: Menambah produk baru
  
  📥 Body: { nama: string, harga: number }
  
  📤 Response: Created product
  
  ✅ Status: 201 Created

- PUT/produk
  📌 Deskripsi: Mengupdate produk berdasarkan ID

  📥 Body: { nama: string, harga: number }

  📤 Response: Updated product

  ✅ Status: 200 OK
  
- DELETE /produk/:id

  📌 Deskripsi: Menghapus produk berdasarkan ID

  📤 Response: Success message

  ✅ Status: 200 OK

### 8. API Endpoints
#### Tambah Produk
- **Form Input**
  - Form sederhana dan mudah digunakan
  - Indikator visual saat mengetik
  - Status loading saat pengiriman data
  - Notifikasi sukses atau error
- **Validasi**
  - Nama produk tidak boleh kosong
  - Harga harus angka positif
  - Batas karakter untuk nama produk
  - Format harga otomatis
  - Penanganan karakter khusus
#### Daftar Produk
- **Tampilan & Desain**
  - Terdapat daftar berisi nama produk
  - Memiliki warna yang sangat _coquette_ dan menggemaskan bagi wanita
- **Fitur**
  - Pembaruan otomatis saat ada perubahan data
  - Mengedit dan menghapus produk
  - Menampilkan notifikasi saat terdapat perubahan data

### 9. Quality Assurance Testing
#### CRUD Operation Testing
- **Create**
  - Validasi ketika menginput nama produk
  - Validasi ketika menginput harga produk
  - Feedback sukses/error
  - Auto-refresh ketika setelah pembuatan produk baru
- **Read**
  - Menampilkan seluruh informasi yang dimasukkan kedalam input
  - Menampilkan format yang benar
- **Update**
  - Validasi input ketika edit

#### UI/UX Testing
- Menampilkan pesan error yang
- Transisi yang smooth
- Loading states jelas
- Responsive

### 10. Performance Testing
- Smooth Scrolling
- Fast Initial Load
- Efficient data fetching

### 11. Troubleshooting

-**Masalah Koneksi Database**
  
  Jika muncul error saat koneksi pada satabase, maka dilakukan langkah berikut:
  - Pastikan PostgreSQL berjalan di pgAdmin 4.
  - Periksa ulang konfigurasi database di file db.js atau .env.
  - Pastikan username, password, dan nama database sudah benar.
  - Cek apakah ada firewall atau antivirus yang memblokir koneksi.
  - Pastikan port PostgreSQL (default: 5432) tidak digunakan aplikasi lain.

-**Masalah Koneksi Database**
  
  Jika aplikasi tidak bisa mengambil data karena CORS error:
  - Pastikan backend berjalan di port yang benar (misalnya 3001).
  - Periksa pengaturan CORS di backend, tambahkan middleware jika perlu
  - Pastikan URL API yang dipanggil di frontend sudah benar.
  - Cek apakah header "Access-Control-Allow-Origin" sudah diatur dengan benar.
  - Pastikan method HTTP (GET, POST, PUT, DELETE) diizinkan oleh backend.

-**Masalah TypeScript**
 
  Jika terjadi error terkait TypeScript, lakukan langkah ini:
  - Jalankan npm install untuk memastikan semua dependencies terpasang.
  - Periksa tipe data di interface seperti Produk.
  - Pastikan setiap props memiliki tipe data yang sesuai.
  - Perbarui TypeScript ke versi terbaru.
  - Bersihkan cache TypeScript dengan tsc --watch --force atau npm run clean.

-**Data Tidak Muncul di Aplikasi**
  
  Jika data tidak tampil di halaman:
  - Periksa koneksi internet jika backend berjalan di server eksternal.
  - Pastikan backend sudah berjalan dan mendengarkan request.
  - Buka Console Browser (F12 > Console) untuk melihat pesan error.
  - Periksa apakah response dari API sesuai dengan format yang diharapkan.
  - Gunakan DevTools Network Tab untuk memeriksa permintaan ke API.
    
-**Masalah Saat Build Aplikasi**
 
  Jika terjadi error ketika menjalankan build (npm run build):
  - Hapus folder node_modules dan file package-lock.json, lalu jalankan ulang npm install.
  - Bersihkan cache dengan npm cache clean --force.
  - Perbarui Node.js ke versi LTS (Long-Term Support).
  - Pastikan semua dependencies kompatibel dengan versi framework yang digunakan.
  - Jika ada error spesifik, cari di log error atau jalankan npm audit fix.
