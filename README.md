# PRD-Catat.in

# Product Requirements Document (PRD)

## Aplikasi Pencatat Tugas Sederhana

## 1. Latar Belakang

Banyak pengguna masih mencatat tugas secara manual di buku catatan, chat pribadi, atau hanya mengingatnya tanpa pencatatan yang jelas. Cara tersebut dapat membuat tugas mudah terlupakan, deadline terlewat, dan pengguna kesulitan membedakan tugas yang sudah selesai dan belum selesai.

Aplikasi **Catat.in** dibuat untuk membantu pengguna mencatat, mengatur, dan memantau tugas harian secara lebih rapi. Aplikasi ini menyediakan fitur seperti menambahkan tugas, menentukan prioritas, memberi deadline, menandai tugas selesai, mengedit tugas, menghapus tugas, serta melihat progres penyelesaian tugas.

## 2. Tujuan Produk

- Membantu pengguna mencatat tugas baru
- Membantu pengguna mengatur prioritas tugas
- Membantu pengguna menentukan deadline tugas
- Menampilkan daftar tugas berdasarkan status
- Memudahkan pengguna menandai tugas yang sudah selesai
- Membantu pengguna melihat progres penyelesaian tugas
- Memudahkan pengguna mengedit dan menghapus tugas

## 3. Target Pengguna

- Mahasiswa yang memiliki banyak tugas kuliah
- Pelajar yang ingin mencatat tugas sekolah
- Pengguna umum yang membutuhkan aplikasi pencatat kegiatan harian
- Pengguna yang ingin mengatur pekerjaan berdasarkan deadline
- Pengguna yang ingin mengetahui progres tugas yang sudah diselesaikan

## 4. Fitur Utama

1. **Dashboard Tugas**

   - Menampilkan nama aplikasi Catat.in
   - Menampilkan jumlah total tugas
   - Menampilkan jumlah tugas selesai
   - Menampilkan jumlah tugas dalam proses
   - Menampilkan progress bar penyelesaian tugas
   - Menampilkan filter tugas berdasarkan Semua, Proses, dan Selesai

2. **Tambah Tugas Baru**

   - Pengguna dapat menambahkan tugas baru
   - Pengguna dapat mengisi judul tugas
   - Pengguna dapat memilih prioritas tugas
   - Pengguna dapat menentukan tanggal dan jam deadline

3. **Pilih Deadline**

   - Pengguna dapat memilih tanggal deadline
   - Pengguna dapat memilih jam deadline
   - Deadline akan tampil pada daftar dan detail tugas

4. **Daftar Tugas**

   - Menampilkan semua tugas yang sudah dibuat
   - Setiap tugas ditampilkan dalam bentuk kartu
   - Informasi tugas berisi judul, status, prioritas, dan deadline

5. **Filter Tugas**

   - Filter Semua menampilkan seluruh tugas
   - Filter Proses menampilkan tugas yang belum selesai
   - Filter Selesai menampilkan tugas yang sudah selesai

6. **Detail Tugas**

   - Menampilkan informasi tugas secara lengkap
   - Pengguna dapat menandai tugas selesai
   - Pengguna dapat mengedit tugas
   - Pengguna dapat menghapus tugas

7. **Centang Selesai**

   - Pengguna dapat menandai tugas yang sudah dikerjakan
   - Status tugas berubah dari proses menjadi selesai
   - Progress penyelesaian tugas ikut berubah

8. **Edit Tugas**

   - Pengguna dapat mengubah judul tugas
   - Pengguna dapat mengubah prioritas
   - Pengguna dapat mengubah deadline

9. **Hapus Tugas**

   - Pengguna dapat menghapus tugas dari halaman detail
   - Pengguna dapat menghapus tugas dengan cara swipe atau geser kartu
   - Jumlah total tugas dan progress akan ikut diperbarui

## 5. User Flow

1. Pengguna membuka aplikasi
2. Pengguna masuk ke halaman utama/dashboard
3. Pengguna melihat ringkasan total tugas, tugas selesai, tugas proses, dan progress
4. Pengguna menekan tombol “Tugas Baru”
5. Pengguna mengisi judul tugas
6. Pengguna memilih prioritas tugas
7. Pengguna menentukan deadline
8. Pengguna menekan tombol “Tambah Tugas”
9. Tugas baru tampil pada daftar tugas
10. Pengguna dapat membuka detail tugas
11. Pengguna dapat menandai tugas selesai, mengedit tugas, atau menghapus tugas
12. Pengguna dapat melihat tugas berdasarkan filter Semua, Proses, dan Selesai

## 6. Kebutuhan Fungsional

- Aplikasi dapat menampilkan dashboard tugas
- Aplikasi dapat menampilkan jumlah total tugas
- Aplikasi dapat menampilkan jumlah tugas selesai
- Aplikasi dapat menampilkan jumlah tugas dalam proses
- Aplikasi dapat menampilkan progress bar penyelesaian tugas
- Aplikasi dapat menambahkan tugas baru
- Aplikasi dapat memilih prioritas tugas
- Aplikasi dapat menentukan deadline tugas
- Aplikasi dapat menampilkan daftar tugas
- Aplikasi dapat memfilter tugas berdasarkan status
- Aplikasi dapat menampilkan detail tugas
- Aplikasi dapat menandai tugas sebagai selesai
- Aplikasi dapat mengedit tugas
- Aplikasi dapat menghapus tugas

## 7. Kebutuhan Non-Fungsional

- UI sederhana dan mudah digunakan
- Dapat berjalan di perangkat Android
- Dibuat menggunakan Flutter
- Tampilan menggunakan warna gelap pada header dan warna ungu sebagai warna utama
- Aplikasi ringan dan responsif
- Tombol dan menu mudah dipahami pengguna
- Data tugas dapat ditampilkan dengan benar
- Progress tugas berubah sesuai data terbaru
- Aplikasi belum menggunakan login atau autentikasi pengguna

## 8. Platform

- Mobile (Android – Flutter)

## 9. Metode Pengembangan

- Menggunakan Flutter
- Desain aplikasi dibuat sederhana dan modern
- Data tugas digunakan untuk kebutuhan pencatatan sederhana
- Pengembangan berfokus pada fitur utama terlebih dahulu
- Fitur yang dibuat meliputi tambah tugas, daftar tugas, filter tugas, detail tugas, edit tugas, hapus tugas, dan progress tugas

## 10. Timeline Sederhana

- Minggu 1: Desain UI aplikasi
- Minggu 2: Implementasi fitur dashboard, tambah tugas, dan daftar tugas
- Minggu 3: Implementasi fitur filter, detail tugas, centang selesai, edit, dan hapus tugas
- Minggu 4: Testing dan perbaikan aplikasi

## 11. Risiko

- Data tugas dapat hilang karena belum menggunakan database online
- Pengguna belum bisa login atau menyimpan data berdasarkan akun
- Belum ada fitur notifikasi pengingat deadline
- Belum tersedia fitur kategori tugas
- Belum tersedia fitur pencarian tugas
- Data belum dapat disinkronkan antar perangkat

## 12. Keberhasilan Produk

- Aplikasi berjalan tanpa error
- Pengguna dapat menambahkan tugas dengan mudah
- Pengguna dapat memilih prioritas dan deadline tugas
- Pengguna dapat melihat daftar tugas berdasarkan status
- Pengguna dapat menandai tugas yang sudah selesai
- Pengguna dapat mengedit dan menghapus tugas
- Progress penyelesaian tugas tampil sesuai data tugas
- Aplikasi dapat digunakan sebagai prototype aplikasi manajemen tugas sederhana



PRD ini dirancang sederhana untuk kebutuhan tugas atau pengembangan awal aplikasi Catat.in.
