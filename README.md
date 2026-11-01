Tugas Pertemuan 10 - Praktikum PBO Python

Mata Kuliah: Pemrograman Berorientasi Objek (Python)

Topik: GUI Sederhana menggunakan Tkinter

Deskripsi

Proyek ini adalah tugas praktikum sesi 1 untuk membuat "Formulir Identitas Mahasiswa". Aplikasi berbasis GUI (Graphical User Interface) ini dibangun murni menggunakan library bawaan Python, yaitu Tkinter. Tujuannya adalah untuk memahami struktur dasar Tkinter dan cara kerja interaksi input-output pada aplikasi desktop.

Fitur Pengembangan

Kode dasar telah dimodifikasi untuk memenuhi 5 syarat tugas pengembangan, antara lain:

Input Alamat (Multi-baris): Menambahkan widget Text untuk mengakomodasi input teks yang lebih panjang.

Tema Visual yang Konsisten: Menggunakan konfigurasi warna background dan foreground melalui variabel, sehingga tampilan aplikasi lebih bersih dan modern.

Validasi Input: Dilengkapi dengan fitur validasi menggunakan messagebox untuk memastikan kolom Nama dan NIM tidak dibiarkan kosong (atau hanya berisi spasi) saat tombol Simpan ditekan.

Layout Grid Manager: Tata letak (layout) dirancang ulang sepenuhnya menggunakan metode .grid() untuk menjaga presisi dan kerapian antar-widget.

Tombol Keluar: Menambahkan tombol khusus (root.destroy) untuk mematikan loop aplikasi secara aman.

Persyaratan Sistem

Python 3.x

Library tkinter (Secara default sudah ter-bundle pada instalasi Python standar)

Cara Menjalankan Program

Buka terminal atau command prompt.

Arahkan direktori (cd) ke lokasi file Python disimpan.

Eksekusi file dengan perintah:

python Tugas_Praktikum.py

Output Pembelajaran

Sesuai dengan target evaluasi pertemuan 10, aplikasi ini berhasil mengimplementasikan pengambilan nilai input, menampilkannya ke layar, mengosongkan formulir, serta menerapkan geometry manager secara mandiri.
