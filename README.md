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
- **Setup Database (PostgreSQL-pgAdmin 4)**
- **Install Dependencies untuk Frontend**
- **Konfigurasi Environment**
- **Jalankan Backend**
- **Jalankan Frontend**

