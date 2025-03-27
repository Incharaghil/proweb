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
│   │   │   └── ProdukList.tsx    # Komponen utama untuk manajemen produk
│   │   ├── App.tsx              # Komponen root
│   │   └── App.css              # Styling global
│   ├── public/                  # Asset statis
│   └── package.json            # Dependencies frontend
└── proweb-backend/
    ├── index.js                # Entry point backend
    ├── db.js                   # Konfigurasi database
    └── package.json           # Dependencies backend
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
