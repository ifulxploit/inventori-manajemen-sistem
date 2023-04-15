# Simple Inventory Management System

<p align="center">
  <img src="https://img.freepik.com/free-vector/conveyor-belt-warehouse-concept-illustration_114360-15026.jpg" alt="inventaris manajemen system">
</p>


## Deskripsi
Program ini adalah sistem manajemen inventaris sederhana yang ditulis dalam bahasa COBOL. Program ini menggunakan file bernama "INVENTORY-FILE" untuk menyimpan data inventaris, dan file lain bernama "INVENTORY-REPORT" untuk menghasilkan laporan barang inventaris yang berada di luar batas minimum dan maksimum.

Program dimulai dengan menampilkan menu dengan lima opsi: menambah inventaris baru, menghapus inventaris, memperbarui inventaris, menampilkan laporan inventaris, dan keluar. Pengguna memilih opsi dengan memasukkan nomor, dan program melakukan tindakan yang sesuai berdasarkan pilihan pengguna.

Jika pengguna memilih untuk menambahkan inventaris baru, program akan meminta pengguna untuk memasukkan kode barang, nama, kuantitas, kuantitas minimum, dan kuantitas maksimum. Kemudian, program akan menuliskan rekaman inventaris ke "INVENTORY-FILE" dan menampilkan pesan berhasil.

Jika pengguna memilih untuk menghapus inventaris, program akan meminta pengguna untuk memasukkan kode barang yang akan dihapus. Jika barang ditemukan dalam file, maka barang tersebut dihapus, dan pesan berhasil ditampilkan. Jika barang tidak ditemukan, maka pesan kesalahan akan ditampilkan.

Jika pengguna memilih untuk memperbarui inventaris, program akan meminta pengguna untuk memasukkan kode barang yang akan diperbarui, serta nilai nama dan kuantitas baru. Jika barang ditemukan dalam file, maka barang tersebut diperbarui dengan nilai baru, dan pesan berhasil ditampilkan. Jika barang tidak ditemukan, maka pesan kesalahan akan ditampilkan.

Jika pengguna memilih untuk menampilkan laporan inventaris, program akan menghasilkan laporan dari semua barang inventaris yang berada di luar batas minimum dan maksimum kuantitas. Laporan ditulis ke file "INVENTORY-REPORT" dan ditampilkan di layar.

Secara keseluruhan, program ini menyediakan fungsi dasar untuk mengelola barang inventaris, termasuk menambah, menghapus, dan memperbarui barang, serta menghasilkan laporan. Namun, program ini tidak termasuk penanganan kesalahan atau validasi input, dan mengasumsikan bahwa "INVENTORY-FILE" sudah diisi dengan data.

## Cara Menjalankan di Windows
1. Pastikan COBOL sudah terinstall di komputer Anda
2. Download atau clone repository ini ke komputer Anda
3. Buka terminal dan arahkan ke direktori repository ini
4. Ketik perintah "`cobc -x main.cbl`" untuk mengkompilasi program
5. Ketik perintah "`./main`" untuk menjalankan program

## Kontribusi

Kami sangat terbuka untuk kontribusi pada program ini. Jika ingin berkontribusi, silakan kirimkan pull request ke repository kami.

## License
Program ini menggunakan lisensi MIT. Silahkan melihat file LICENSE.md untuk informasi lebih lanjut.

## Tentang Penulis

Nama penulis program ini adalah ifulxploit. Anda dapat mengunjungi website saya di https://ifulxploit.github.io/ atau mengirim email ke ifulxploit@gmail.com.
