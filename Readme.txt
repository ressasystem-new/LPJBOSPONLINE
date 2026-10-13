# Sistem LPJ BOSP (Laporan Pertanggungjawaban Dana Bantuan Operasional Satuan Pendidikan)

Aplikasi berbasis web modern dan responsif untuk membantu satuan pendidikan dalam mengelola, mengekstrak, dan mencetak Dokumen Laporan Pertanggungjawaban (LPJ) Dana BOSP secara online[cite: 1].

## 🚀 Fitur Utama

- **Data Master Satuan Pendidikan**: Pengaturan data sekolah, Kepala Sekolah, Bendahara, serta manajemen Toko Mitra/Penyedia dan Penerima[cite: 1].
- **Upload & Ekstraksi BKU (PDF)**: Unggah file PDF Buku Kas Umum (BKU), dan sistem akan secara otomatis mengekstrak data transaksi ke dalam bentuk tabel[cite: 1].
- **Pembuatan LPJ Fleksibel**:
  - Fitur penggabungan uraian dan pengeluaran BPU/BNU dengan nama yang sama[cite: 1].
  - Klasifikasi transaksi (Jasa, Rutin, Barang, Perjalanan Dinas, Konsumsi)[cite: 1].
  - Upload lembar nota/struk asli serta dokumentasi foto fisik barang/jasa[cite: 1].
- **Pencetakan Dokumen Resmi**: Pratinjau dan unduh kuitansi pembayaran beserta kelengkapannya dalam format PDF menggunakan pustaka `jsPDF`[cite: 1].
- **Personalisasi Tampilan & Pengaturan**: Kustomisasi warna tema, ukuran font, logo instansi, latar belakang, hingga tata letak antarmuka sesuai keinginan[cite: 1].

## 🛠️ Teknologi yang Digunakan

- **HTML5 & CSS3** (dengan *CSS Variables* untuk kustomisasi tema dinamis)[cite: 1]
- **JavaScript (ES6+)**[cite: 1]
- **PDF.js** (untuk membaca dan mengekstrak teks dari file PDF BKU)[cite: 1]
- **jsPDF** (untuk pembuatan dokumen PDF kuitansi dan laporan)[cite: 1]

## 💻 Cara Menjalankan Aplikasi

Aplikasi ini berjalan secara *client-side* (di sisi peramban web). Anda tidak memerlukan instalasi peladen (*server*) khusus untuk menjalankannya.

1. Unduh atau salin seluruh kode program (file `index.html`) ke komputer Anda.
2. Buka file `index.html` menggunakan peramban web modern (seperti Google Chrome, Mozilla Firefox, atau Microsoft Edge).
3. Aplikasi siap digunakan! Seluruh data transaksi dan pengaturan Anda akan tersimpan secara otomatis di dalam penyimpanan lokal peramban (*LocalStorage*).

## 📄 Hak Cipta & Informasi

Dikembangkan untuk mendukung pelaporan Dana BOSP pada Dinas Pendidikan dan Kebudayaan Kota Manado[cite: 1].