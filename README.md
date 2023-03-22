# LATIHAN5DPBO2023

Latihan 5 DPBO Program Java sederhana dengan GUI NetBeans untuk Daftar Mahasiswa

##Janji

Saya Destira Lestari Saraswati NIM 2100506 mengerjakan soal Latihan 5 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Description

Program ini merupakan aplikasi desktop sederhana yang digunakan untuk memasukkan, mengubah, dan menghapus data mahasiswa pada sebuah tabel. Dalam program ini, pengguna dapat menambahkan data mahasiswa baru, mengedit data mahasiswa yang sudah ada, menghapus data mahasiswa, dan melihat daftar seluruh data mahasiswa yang telah disimpan.

### Fitur

Program ini memiliki fitur untuk `menambahkan`, `mengubah`, dan `menghapus` data mahasiswa. Data mahasiswa disimpan pada sebuah `ArrayList`. Antarmuka grafis terdiri dari `field` untuk memasukkan data seperti `NIM, NAMA, NILAI`, dan `GENDER` dalam `combobox option`, serta tombol-tombol untuk melakukan operasi `tambah`, `ubah`, `hapus`, dan `batal`.

Ketika tombol **"Add"** ditekan, program akan melakukan validasi terhadap data yang dimasukkan pengguna. Validasi dilakukan untuk memastikan bahwa data yang dimasukkan sesuai dengan format yang diinginkan. Misalnya, program akan melakukan validasi terhadap NIM untuk memastikan bahwa NIM yang dimasukkan hanya berupa angka. Jika data tidak sesuai dengan format yang diinginkan, program akan menampilkan pesan peringatan dan meminta pengguna untuk memasukkan data yang valid.

Data mahasiswa yang telah dimasukkan akan ditampilkan dalam sebuah `tabel`.

Meskipun program ini tidak menggunakan database, namun ArrayList dapat menyimpan data secara sementara selama program dijalankan. Namun, data akan hilang saat program ditutup. Jika ingin menyimpan data secara permanen, dapat menggunakan file input/output atau database.

>Fitur Validasi

1. Form NIM
  * NIM harus diisi
  * NIM harus berupa angka
  
2. Form Nama
  * Nama harus diisi
  
3. Form Nilai
  * Nilai harus diisi
  * Nilai hanya boleh berisi huruf kapital A sampai E atau huruf kapital dengan tanda '-' atau '+'
  
4. Form Gender
  * Jenis kelamin harus dipilih

## Getting Started

### Dependencies

1. JDK (Java Development Kit) - merupakan kit pengembangan perangkat lunak yang digunakan untuk mengembangkan aplikasi Java.

2. NetBeans - merupakan Integrated Development Environment (IDE) yang digunakan untuk membuat program Java dengan GUI.

3. Swing - merupakan library GUI yang digunakan dalam pembuatan program GUI dengan NetBeans.

4. JOptionPane - merupakan library yang digunakan untuk menampilkan pesan dialog kepada pengguna.

5. ArrayList - merupakan struktur data yang digunakan untuk menyimpan data mahasiswa dalam program.

6. RegEx (Regular Expression) - merupakan sebuah library untuk melakukan validasi data dengan menggunakan pola atau regular expression.


### Executing program

* How to run the program
  * Pilih file DaftarMahasiswa_3_1.jar
  * Klik dua kali pada nama file di atas

### Catatan

Program ini masih bersifat sederhana dan dapat dikembangkan lebih lanjut sesuai kebutuhan. Program ini juga dapat disesuaikan dengan menggunakan database yang berbeda atau mengubah tampilan antarmuka grafisnya.

### Screenshoot Program
![alt text](LATIHAN5DPBO2023/Screenshots/1.jpeg "Tampilan Awal")
