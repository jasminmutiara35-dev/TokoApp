
# TokoApp

Aplikasi TokoApp merupakan aplikasi desktop berbasis Java yang dikembangkan menggunakan JavaFX untuk membangun GUI. Aplikasi ini dibuat untuk mengelola data produk toko berdasarkan kode produk, nama produk, kategori, dan harga. Pengguna dapat menambahkan produk, melihat daftar produk, mencari produk, serta melihat detail produk yang dipilih.

## Fitur

- Menambahkan data produk baru.
- Input kode produk.
- Input nama produk.
- Pilihan kategori produk (Makanan atau Minuman).
- Input harga produk dalam satuan Rupiah (Rp).
- Menampilkan daftar produk dalam bentuk tabel.
- Mencari produk berdasarkan nama.
- Menampilkan detail produk yang dipilih.
- Validasi input untuk memastikan nama produk tidak kosong dan harga lebih dari nol.

## Teknologi yang Digunakan

- Java JDK 17
- JavaFX 21
- Apache Maven
- Apache NetBeans IDE
- Scene Builder

## Tampilan Aplikasi

<img width="1919" height="1014" alt="Screenshot 2026-11-09 133356" src="https://github.com/user-attachments/assets/70c02b58-9fd6-48aa-a0e8-ee3368469be5" />
<img width="1919" height="1011" alt="Screenshot 2026-11-09 133341" src="https://github.com/user-attachments/assets/93165692-0ff8-49b2-b2bd-480309a40e09" />
<img width="1919" height="1004" alt="Screenshot 2026-11-09 133422" src="https://github.com/user-attachments/assets/d65b1f04-b1c3-4519-b5b9-fc868386d2f5" />




## Struktur Project

```text
TokoBaruApp/
├── src/
│   └── main/
│       ├── java/
│       │   └── kelas/
│       │       ├── controller/
│       │       ├── data/
│       │       ├── model/
│       │       ├── MainApp.java
│       │       └── Navigator.java
│       └── resources/
│           └── kelas/
│               ├── daftar.fxml
│               ├── detail.fxml
│               ├── form.fxml
│               └── styles/
│                   └── app.css
├── pom.xml
└── README.md
```

## Cara Menjalankan

### 1. Clone Repository

Buka terminal atau Command Prompt, kemudian jalankan:

```bash
git clone https://github.com/jasminmutiara35-dev/TokoApp
```

### 2. Masuk ke Direktori Project

```bash
cd TokoBaruApp
```

### 3. Periksa Instalasi Java dan Maven

Pastikan Java dan Maven sudah terpasang:

```bash
java -version
mvn -version
```

### 4. Buka Project

Buka Apache NetBeans, kemudian pilih **File → Open Project**. Cari folder project `TokoBaruApp`.

### 5. Jalankan Aplikasi

Buka terminal pada direktori utama project, kemudian jalankan:

```bash
mvn javafx:run
```

Tunggu hingga proses build selesai. Jika berhasil, aplikasi TokoBaruApp akan terbuka.

## Cara Menggunakan Aplikasi

1. Jalankan aplikasi TokoBaruApp.
2. Klik tombol **Tambah Produk**.
3. Masukkan kode produk pada kolom yang tersedia.
4. Masukkan nama produk.
5. Pilih kategori Makanan atau Minuman.
6. Masukkan harga produk.
7. Klik tombol **Simpan Produk**.
8. Produk yang berhasil ditambahkan akan ditampilkan pada tabel.
9. Gunakan fitur **Cari** untuk mencari produk berdasarkan nama.
10. Pilih produk, kemudian klik **Lihat Detail** untuk melihat informasi produk.

---
