# Teks Prosedur Video
## Langkah-langkah Membuat *database* dengan MySql
1)	Pastikan anda sudah menginstall MySql, untuk mengecek silahkan buka terminal, kemudian ketik “`mysql —version`” jika tidak ada, tambahkan direktori mysql ke path 
2)	Jika sudah, silahkan masuk sebagai *super user*, biasanya secara default *username* adalah `root` dan *password*  kosong. Jadi ketik “`mysql -u root -p` “
3)	Ketika sudah masuk, anda bisa mengetik “`SHOW DATABASES;`” untuk melihat seluruh *database* yang ada. *Syntax Mysql* tidak sensitif, jadi huruf besar dan kecil tidak berpengaruh dan jangan lupa menambahkan `;` di akhir setiap perintah mysql
4)	Untuk membuat *database* baru, ketik “`CREATE DATABASE nama_database;`”, contoh “`CREATE DATABASE barang` ”. Ketik “`SHOW DATABASES;`” untuk melihat apakah *database* sudah dibuat atau belum
5)	Didalam *database* kita bisa membuat tabel yang kurang lebih mirip seperti tabel di *excel*  atau *Google Spreadsheet* 
6)	Untuk membuat tabel kita harus memilih *database* dulu dengan perintah “USE nama_data”, contohnya kita akan memilih *database barang*, “`USE DATABASE barang; `”
7)	Ketika sudah masuk kita bisa mengetik perintah *CREATE TABLE nama_tabel* diikuti dengan tipe data. Misalkan “`CREATE TABLE sembako (nama_barang VARCHAR(100), stok INT, harga INT);`”, untuk melihat silahkan ketik “`DESC sembako;`”
8)	Lalu memasukan data silahkan ketik  “`INSERT INTO sembako(nama_barang, stok, harga) VALUES (‘gula’, 5, 4500);`”
9)	Kemudian  ketik “`SELECT * FROM sembako;`” untuk melihat seluruh data dalam tabel barang
10)	Selesai, anda sudah bisa membuat dan menambahkan data didalam *database*
