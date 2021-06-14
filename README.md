# Latihanku-Perpustakaan

[1]Deskripsi Program

Program menggunakn bahasa pemrograman Python berextension file .ipynb
Program dapat dijalankan di Visual Studio Code, Jupyter Notebook, Google Colab, dan beberapa perangkat yang mendukung
Menggunakan file .csv sebagai dataset/databset dari program
[2]Detail Akun Program

Terdapat 2 akun yaitu User dan Admin
Admin dapat mengakses tampilan Buku, dan Admin memiliki permission CRUD(Create, Read, Update, Delete) pada buku yang ada 
dan dapat melihat semua tampilan mahasiswa/dosen yang meminjambuku

[3]Tampilan Awal Program

Ditampilkan pada pilihan Register/Login

 1.1 Register
     Mengisi Nama Mahasiswa, Kategori, NIM, Jurusan, dan Angkatan  sebagai daftar akun pada program
     1.1.1 Nama Mahasiswa
           Nama Mahasiswa dapat berisikan gabungan string dan integer
     1.1.2 Kategori
           Terdapat 2 kategori yaitu Dosen, dan Mahasiswa. Untuk kategori Admin sudah terdapat dalam dataset
     1.1.3 NIM
           NIM berisikan integer
     1.1.4 Jurusan
           Jurusan terbagi menjadi Teknik dan Informatika, Seni dan Design, Bisnis dan Manajemen, Film dan Animasi, Komunikasi dan Jurnalistik
     1.1.5 Angkatan
           Angkatan masuk dari range tahun 2006 hingga tahun 2021(Tahun sekarang)
 1.2 Login
     Jika sudah mempunyai akun bisa langsung menggunakan pilihan login, jika belum harus 
     mendaftarkan akun terlebih dahulu dan langsung diarahkan ke login
 1.3 Forgot Password
     Forgot Password/Lupa Password digunakan untuk mengganti password sebelumnya dengan mengisi 
     username dan pin, jika username dan pin ditemukan maka bisa melakukan pergantian password
     
[4]Menu Program

Tampilan Mahasiswa dan Dosen dapat mengakses semua list buku

 1.1 Read Buku dan Pinjam Buku 
     Mahasiswa dapat melihat semua list buku dan dapat meminjam buku tersebut apabila status "Tersedia". 
     Setiap Mahasiswa/Dosen hanya bisa meminjam buku sebanyak 2 buku
 1.2 Tampilkan Buku
     Mahasiswa/Dosen dapat melihat semua buku yang terdapat dalam dataset/database
     1.2.1 Tampilkan Semua Buku
           Menampilkan semua buku yang tersedia
     1.2.2 Filter Buku
           Buku yang ditmapilkan disesuai dengan Genre yang dimasukkan
     1.2.3 Cari Buku
           Mencari buku sesuai Nama yang lebih spesifik    
 1.3 Pengembalian Buku
     Mahasiswa/Dosen yang meminjam buku bisa juga untuk mengembalikkan buku yang telah dipinjam
           
Tampilan Admin dapat mengakses Buku

 2.1 Tambah Buku
     Admin dapat menambahkan Buku baru ke dalam dataset/database
 2.2 Update Buku
     Admin dapat memperbaharui Nama Buku, Tahun Terbit, Genre, ISSN, Status
 2.3 Delete Buku
     Admin juga dapat menghapus buku yang sudah dilist dalam daftar buku
     
[5]Lampiran Dilampirkan berupa file:

account.csv Berfungsi untuk menampung semua akun yang dimasukkan ke dalam dataset/database
market.csv Berfungsi untuk menampung semua barang
bill.csv Berfungsi untuk menampung pesanan barang belanjaan
loginaccount.csv Berfungsi untuk mengambil data akun yang sedang login
Swalayan.ipynb Program yang akan dijalankan

[7]Referensi

StackOverflow
GeeksforGeeks
Ritchie Ng
Real Python
Documentations
Last Update : 06/014/2021 8:06 PM
