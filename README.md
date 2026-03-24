## 👨‍💻 Author

* Husein Sidharta Muhammad
* NIM: 245150707111040

# 📚 Laravel Book API

RESTful API berbasis Laravel untuk mengelola data buku dengan fitur CRUD lengkap (list, create, show, update, delete). API ini menggunakan MySQL sebagai database dan dilengkapi dokumentasi otomatis menggunakan Scramble (OpenAPI).

---

## 🚀 Features

* 📖 List semua buku
* ➕ Tambah buku
* 🔍 Detail buku
* ✏️ Update buku
* ❌ Hapus buku
* 📄 Dokumentasi API otomatis (Scramble)

---

## 📌 API Endpoints

Base URL:

```
/api/v1/books
```

| Method    | Endpoint           | Description      |
| --------- | ------------------ | ---------------- |
| GET       | /api/v1/books      | Ambil semua buku |
| POST      | /api/v1/books      | Tambah buku      |
| GET       | /api/v1/books/{id} | Detail buku      |
| PUT/PATCH | /api/v1/books/{id} | Update buku      |
| DELETE    | /api/v1/books/{id} | Hapus buku       |

---

## ⚙️ Cara Install & Menjalankan

1. Clone repository:

```bash
git clone https://github.com/huseinsm/api-book.git
cd api-book
```

2. Install dependency:

```bash
composer install
```

3. Copy file environment:

```bash
cp .env.example .env
```

4. Generate app key:

```bash
php artisan key:generate
```

5. Setup database di file `.env`:

```
DB_DATABASE=api_book
DB_USERNAME=root
DB_PASSWORD=
```

6. Jalankan migration:

```bash
php artisan migrate
```

7. Jalankan server:

```bash
php artisan serve
```

---

## 📄 Dokumentasi API (Scramble)

Dokumentasi API dibuat otomatis menggunakan Scramble.

Untuk melihat dokumentasi:

1. Jalankan server Laravel:

```bash
php artisan serve
```

2. Buka di browser:

```
http://127.0.0.1:8000/docs/api
```

---

## 📸 API Documentation Preview



> ⚠️ Dokumentasi hanya dapat diakses secara lokal karena aplikasi belum di-deploy.
![API Docs](assets/docs-preview.jpg)
---
