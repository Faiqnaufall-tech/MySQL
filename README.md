## MySQL
> Sumber : Programmer Zaman Now

**Database**  
Database adalah tempat kita menyimpan table di MySQL, jika misalkan table di MySQL adalah sebuah file, maka database adalah folder nya, yang dimana bisa menyimpan banyak table di sebuah database. Untuk sebuah aplikasi biasanya hanya memakai 1 database saja, jarang ada aplikasi yang connect ke 2 database, jadi biasanya hanya membuat sebuah 1 database saja yang bisa dibuat menjadi subdatabase, seperti gambar  berikut:  

<img width="761" height="432" alt="mysqlll" src="https://github.com/user-attachments/assets/67f9bf5f-1aee-4726-b4f2-b25a2b396f84" />

**Perintah dasar MySQL**

| Command | Fungsi |
| ------------ | ------------ |
| `show databases;` |  Untuk menampilkan semua Database |
| `create database nama_database` | membuat sebuah database baru |
| `drop database nama_database` | menghapus database |
| `use nama_database` | memilih database |
| `show tables` | menampilkan table di database |  

**Tipe Data**  
tipe data di MySQL itu hanya bisa digunakan per kolom, jadi misal kan kolom 1 terdapat tipe data number berarti kolom tersebut harus bertipe data number semua tetapi di tipe data text itu kita bisa menginputkan number cuman kalau tipe data number itu gak bisa di inputkan text, contoh nya seperti berikut:  

<img width="1075" height="466" alt="tipedatamysql" src="https://github.com/user-attachments/assets/06a1bd28-e0c9-4fde-aa7f-9b9a5a0ace15" />  

**Tipe Data Number**  
secara garis besar tipe data number di MySQL itu ada dua jenis yaitu *Integer* atau tipe number bilangan bulat, *floating point* atau tipe data number pecahan.  

*contoh tipe data interger*  

<img width="1244" height="472" alt="tipedataint" src="https://github.com/user-attachments/assets/7b86aac3-75cf-4efb-b1d4-ad1b9888cfd7" />  

  
*contoh tipe data floating point*  

<img width="1244" height="374" alt="tipedatafloating" src="https://github.com/user-attachments/assets/5303b59c-d00e-4ca9-9c10-83f25326a599" />


