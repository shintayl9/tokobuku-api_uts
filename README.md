Praktikum
Persiapan

1. Instalasi Laravel 11:
   ![Screenshot tokobuku-api](images/1.png)
   ![Screenshot tokobuku-api](images/2.png)
   ![Screenshot tokobuku-api](images/3.png)

2. Konfigurasi Database
   ![Screenshot tokobuku-api](images/4.png)
   ![Screenshot tokobuku-api](images/5.png)

3. Migrasi Awal
   ![Screenshot tokobuku-api](images/6.png)

Membuat API CRUD untuk Sistem Toko Buku
API ini akan mengelola data buku dan kategori dengan beberapa endpoint:

1. Kategori: Menambahkan dan menampilkan kategori buku.
2. Buku: Mengelola informasi buku (judul, penulis, harga, stok, dan kategori).

3. Membuat Migration dan Model
   Membuat migration dan model untuk Kategori dan Buku:
   ![Screenshot tokobuku-api](images/7.png)

Edit file migration `create_kategoris_table.php`:
![Screenshot tokobuku-api](images/8.png)

Edit file migration `create_bukus_table.php`:
![Screenshot tokobuku-api](images/9.png)
![Screenshot tokobuku-api](images/10.png)

2. Membuat Controller API untuk Kategori dan Buku
   ![Screenshot tokobuku-api](images/11.png)

Isi file `KategoriController.php`:
![Screenshot tokobuku-api](images/12.png)

Isi file `BukuController.php`:
![Screenshot tokobuku-api](images/13.png)
