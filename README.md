# 📚 Bookshelf API

Bookshelf API adalah sebuah proyek backend sederhana yang dikembangkan oleh **taehyung-wife** sebagai bagian dari proses pembelajaran **Belajar Membuat Aplikasi Back-End untuk Pemula** di Dicoding Academy.

## 📝 Deskripsi

Proyek ini merupakan implementasi dari sebuah RESTful API yang memungkinkan pengguna untuk:

- Menambahkan buku
- Melihat seluruh daftar buku
- Melihat detail buku berdasarkan ID
- Mengubah data buku
- Menghapus buku

Semua data disimpan sementara dalam memori (in-memory array), sehingga setiap restart server akan menghapus data yang ada.

## ⚙️ Teknologi yang Digunakan

- **Node.js** – sebagai runtime JavaScript di server
- **Nodemon** – untuk kemudahan development dengan auto-restart saat ada perubahan
- **Hapi.js** – framework ringan untuk membangun server dan route handler
- **ESLint** – untuk memastikan kualitas dan konsistensi kode JavaScript

## 🚀 Cara Menjalankan Proyek

1. **Clone repo ini** ke lokal:

   ```bash
   git clone https://github.com/alditasptnsr/bookshelf-api.git
   cd bookshelf-api
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Jalankan server**:

   ```bash
   npm run start
   ```

   Atau jika kamu ingin live reload saat develop:

   ```bash
   npx nodemon src/server.js
   ```

4. **API akan tersedia di**: `http://localhost:9000`

## 📌 Endpoint Utama

| Method | Endpoint      | Deskripsi                  |
| ------ | ------------- | -------------------------- |
| POST   | `/books`      | Tambah buku baru           |
| GET    | `/books`      | Ambil semua buku           |
| GET    | `/books/{id}` | Ambil detail buku tertentu |
| PUT    | `/books/{id}` | Perbarui data buku         |
| DELETE | `/books/{id}` | Hapus buku                 |

## ✍️ Penulis

Dibuat dengan semangat belajar oleh **taehyung-wife**  
Sebagai bagian dari submission untuk kelas Dicoding: _Belajar Membuat Aplikasi Back-End untuk Pemula_.

---

Silakan gunakan dan modifikasi proyek ini sesuai kebutuhan pembelajaran atau eksperimen kamu.
