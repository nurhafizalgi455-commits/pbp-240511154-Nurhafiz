# LKP 4A - RESTful API Sederhana dengan Express.js

**Nama:** Nurhafiz Alghifari  
**NIM:** 240511154  
**Kelas:** TI24F  

## Cara Menjalankan
1. Jalankan `npm install`
2. Jalankan `npm run dev` (server aktif di `http://localhost:3000`)

## Dokumentasi Endpoint
| Method | Endpoint | Fungsi | Body JSON | Status Code |
| :--- | :--- | :--- | :--- | :--- |
| GET | `/api/items` | Ambil semua data item | - | 200 |
| GET | `/api/items/:id` | Ambil 1 data item berdasarkan ID | - | 200 / 404 |
| POST | `/api/items` | Tambah item baru | `{"nama": "Keyboard", "harga": 300000}` | 201 / 400 |
| PUT | `/api/items/:id` | Update item berdasarkan ID | `{"harga": 7500000}` | 200 / 404 |
| DELETE | `/api/items/:id` | Hapus item berdasarkan ID | - | 200 / 404 |