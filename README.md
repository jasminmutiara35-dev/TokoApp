
# TokoApp
Aplikasi TokoApp merupakan aplikasi desktop berbasis Java yang dikembangkan menggunakan JavaFX untuk membangun Graphical User Interface. Aplikasi ini dibuat untuk mengelola data produk toko, mulai dari menambahkan produk, menampilkan daftar produk, mencari produk, hingga melihat detail produk.
# Fitur
- Menambahkan data produk baru.
- Input kode produk dan nama produk.
- Memilih kategori produk (Makanan atau Minuman).
- Input harga produk.
- Menampilkan daftar produk dalam bentuk tabel.
- Mencari produk berdasarkan nama.
- Menampilkan detail produk yang dipilih.
- Validasi nama produk dan harga.
# Teknologi yang Digunakan
- Java JDK 17
- JavaFX 21
- Apache Maven
- Apache NetBeans IDE
- Scene Builder
# Tampilan Aplikasi
Tambahkan screenshot halaman daftar produk, form tambah produk, dan detail produk pada bagian ini.
# Struktur Project
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


# Cara Menjalankan
1. Clone Repository
Buka terminal atau Command Prompt, kemudian jalankan:
 https://github.com/jasminmutiara35-dev/TokoApp


3. Masuk ke Direktori Project
cd TokoApp


4. Periksa Instalasi Java dan Maven
Pastikan Java dan Maven sudah terpasang:
java -version
mvn -version


5. Buka Project
Buka Apache NetBeans, kemudian pilih File → Open Project. Cari folder project TokoApp.
6. Jalankan Aplikasi
Buka terminal pada direktori utama project, kemudian jalankan:
mvn javafx:run


# Cara Menggunakan Aplikasi
1. Jalankan aplikasi TokoBaruApp.
2. Pilih menu Tambah Produk.
3. Masukkan kode produk.
4. Masukkan nama produk.
5. Pilih kategori Makanan atau Minuman.
6. Masukkan harga produk.
7. Klik tombol Simpan Produk.
8. Produk akan ditampilkan pada tabel daftar produk.
9. Gunakan fitur Cari untuk menemukan produk berdasarkan nama.
10. Pilih produk dan klik Lihat Detail untuk melihat informasi produk.
