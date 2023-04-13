# data mahasiswa
<<<<<<< HEAD
 # 1. Buat sebuah database dengan nama latihan2!
mysql> create database latihan02;
=======
# 2. Buat sebuah tabel dengan nama biodata (nama, alamat) didalam database latihan1!

mysql>create table biodata (nama varchar (15), alamat varchar (15));
![gambar1](https://github.com/rahmathdyat/datamahasiswa/blob/main/SsBasisData/Screenshot%20(3).png)

# 3. Tambahkan sebuah kolom keterangan (varchar 15), sebagai kolom terakhir!
mysql> alter table biodata add column keterangan varchar (15);
mysql> desc biodata
![gambar1](https://github.com/rahmathdyat/datamahasiswa/blob/main/SsBasisData/Screenshot%20(4).png)

# 4. Tambahkan kolom id (int 11) di awal (sebagai kolom pertama)!
 mysql> alter table biodata add column id int(11) first;
 ![gambar1](https://github.com/rahmathdyat/datamahasiswa/blob/main/SsBasisData/Screenshot%20(5).png)

# 5. Sisipkan sebuah kolom dengan nama phone (varchar 15) setelah kolom alamat!
mysql> alter table biodata add column phone varchar(15) after alamat;
mysql> desc biodata;
![gambar1](https://github.com/rahmathdyat/datamahasiswa/blob/main/SsBasisData/Screenshot%20(6).png)

# 6. Ubah tipe data kolom id menjadi char(11)!
mysql> alter table biodata modify column id char (11);
![gambar1](https://github.com/rahmathdyat/datamahasiswa/blob/main/SsBasisData/Screenshot%20(7).png)

# 7. Ubah nama kolom phone menjadi hp (varchar 20)!
mysql> alter table biodata change column phone hp varchar(20);
mysql> desc biodata;
![gambar1](https://github.com/rahmathdyat/datamahasiswa/blob/main/SsBasisData/Screenshot%20(8).png)

# 8. Tambahkan kolom email setelah kolom hp!
mysql> alter table biodata add column email varchar(11) after hp;
mysql> desc biodata;
![gambar1](https://github.com/rahmathdyat/datamahasiswa/blob/main/SsBasisData/Screenshot%20(9).png)

# 9. Hapus kolom keterangan dari tabel!
mysql> alter table biodata drop column keterangan;
![gambar1](https://github.com/rahmathdyat/datamahasiswa/blob/main/SsBasisData/Screenshot%20(10).png)



# C.	Data dan Analisis 
## 1.	Apa maksud dari Int (11)?
Maksud dari int (11) adalah nama tipe datanya adalah integer dan memiliki panjang 11 karakter.
## 2.	Ketika kita melihat sturktur tabel dengan perintah desc, ada kolom Null yang berisi Yes dan No, apa maksudnya?
Apabila Null berisi no, maka data tersebut nantinya akan dilakukan pengisian atau penginputan. Sedangkan apabila Null berisi yes, maka artinya data tersebut akan dikosongkan atau tidak dilakukan penginputan.










=======



>>>>>>> 026813af7fa049f74b5ee14a7526eaf48edf779c