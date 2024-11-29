# UTS Pemrograman Berorientasi Obyek 1
- Mata Kuliah : Pemrograman Berorientasi Obyek 1
- Dosen Pengampu : Muhammad Ikhwan Fathulloh
## Profil
- Nama : Nisa Silva Triana
- NPM : 23552011094
- Studi Kasus : Aplikasi Manajemen Keuangan
## Judul Studi Kasus
Aplikasi Manajemen Keuangan
## Penjelasan Studi Kasus
Penerapan konsep OOP, seperti Inhertance, Polymorphism, Encapsulation, Abstraction dalam pengembangan Aplikasi Manajemen Keuangan.
## Penjelasan 4 pilar OOP dalam studi kasus
### 1. Inhertance
Kelas rekening menjadi induk dengan atribut umum seperti nomor rekening, saldo dan jenis rekening. Kelas turunan seperti Rekening Tabungan dan Rekening Giro mewarisi atribut tersebut, sekaligus menambah fitur tambahan masing masing jenis rekening.
### 2. Polymorphism
Dalam metode perhitungan bunga, tiap jenis rekening memiliki cara perhitungan yang berbeda. Sebagai contoh, Rekening Tabungan menghitung bunga berdasarkan saldo harian, sedangkan Rekening Giro menghitungnya berdasarkan saldo bulanan.
### 3. Encapsulation
Informasi tentang transaksi keuangan, seperti tanggal, jumlah nominal dan jenis transaksi disembunyikan di dalam kelas Transaksi. Pengguna hanya dapat mengakses atau mengubah data tersebut melalui metode aman seperti setTransaksi().
### 4. Abstraction
Layanan keuangan adalah kelas abstrak yang berisi metode umum seperti setor() dan tarik(). Metode ini nantinya akan di implementasikan oleh kelas spesifik seperti Tabungan.
## Demo Proyek
- Github: https://github.com/NisaSilvaTriana/UTS_PBO1_TIF-23A_23552011094/tree/master
- Drive: https://drive.google.com/file/d/1E---9pWtdgrE30FEeMHrTEsz6RGAyh8w/view?usp=drive_link
