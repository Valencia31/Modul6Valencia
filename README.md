# Modul6Valencia
Latihan 1
![alt text](https://github.com/Valencia31/Modul6Valencia/blob/master/latihan%201%20cookie.JPG?raw=true)
Latihan 2
![alt text](https://github.com/Valencia31/Modul6Valencia/blob/master/latihan%202%20cookie.JPG?raw=true)
Latihan 3
![alt text](https://github.com/Valencia31/Modul6Valencia/blob/master/latihan%203%20cookie.JPG?raw=true)
Latihan 4
![alt text](https://github.com/Valencia31/Modul6Valencia/blob/master/latihan%204%20cookie.JPG?raw=true)
Latihan 5
![alt text](https://github.com/Valencia31/Modul6Valencia/blob/master/latihan%205%20cookie.JPG?raw=true)
Latihan 6
![alt text](https://github.com/Valencia31/Modul6Valencia/blob/master/LOGIN%20COOKIE.JPG?raw=true)
![alt text](https://github.com/Valencia31/Modul6Valencia/blob/master/LOGIN1%20COOKIE.JPG?raw=true)
Pratikum
![alt text](https://github.com/Valencia31/Modul6Valencia/blob/master/pratikum1%20cookie.JPG?raw=true)
![alt text](https://github.com/Valencia31/Modul6Valencia/blob/master/pratikum2%20cookie.JPG?raw=true)
Pertanyaan
1.)
cookie
1. Cookies disimpan di sisi klien
2. Cookies tidak aman bagi klien karena cookies dapat disisipi program yang tidak diketahi klien.
Karena cookies tidak aman maka browser klien dapat di-set untuk menghapus cookies dan bahkan men-disable fungsi cookies. Menurut sumber lain cookies juga tidak aman bagi sisi server karena cookies dapat di-edit oleh klien.
3. Data yang disimpan ke dalam metode cookies dapat bertahan lebih lama dan dapat diatur waktu expired-nya.
session
1. Disimpan disisi server
2. Lebih aman karena tidak ada file yang dimasukan ke sisi klien
3. Setelah web browser klien dimatikan maka data yang disimpan metode session akan hilang dan waktu expired juga tidak dapat diatur.
2.)1. Pilih tools menu pada bagian atas browser mozilla, Click “Tools” -> “Options”
2. Pilih “Privacy” pada menu.
3. Pada bagian Firefox will pilih “Use custom settings for history”
4. Pilih “Show Cookies”
5. Pilih Cookies yang terdapat pada list yang muncul kemudian klik “Remove Cookies” untuk menghapus cookies pada list satu persatu namun untuk dapat menghapus semua cookies yang terdaftar anda dapat memilih “Remove All Cookies”
6. Pilih “OK atau Close”
3.)
session<php

session_name(“verify”);  //menciptakan session bernama verify

session_start();  //memulai session

$username=”nama pengguna”;

$password=”kata sandi”;

$_SESSION[‘ses_username’]=$username;    //mengisi session

$_SESSION[‘ses_password’]=$password;

Echo(“<a href=session2.php’>File Kedua</a>”);

?>
cookie
<?php

$isi_username=”nama pengunjung”;

$isi_password=”kode sandi”:

setcookie(“username”,$isi_username):

setcookie(“password”,$isi_password);

echo (“<a href =’cookie2.php’>File Kedua</a>”);

?>

