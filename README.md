# WEB-SERVER
Web server adalah sebuah software (perangkat lunak) yang memberikan layanan berupa data. Berfungsi untuk menerima permintaan HTTP atau HTTPS dari klien atau kita kenal dengan web browser (Chrome, Firefox). Selanjutnya ia akan mengirimkan respon atas permintaan tersebut kepada client dalam bentuk halaman web.
# TOOLS DAN SERVICE YANG DI GUNAKAN 
Ubuntu versi 22.04  

virtual box versi 7.10

Apache2

winscp  

# PERKEMBANGAN WEB SERVER
1. 17 oktober 2023 installasi ubuntu
2. 7 desember 2023 install apache2
3. 10 desember 2023 memasukan index.html ke ubuntu server
   
# INSTALL APACHE2
1. sudo apt install apache2
2. service apache2 status
3. kemudian cek dengan mengetikan ip address di browser
4. ls /var/www/html/
5. cd /var/www/html/index.html(untuk mengecek index.html bawaan ubuntu)
6. kemudian untuk memindahkan indek.html yang kita buat sendiri maka memerlukan app winscp
7. saat berada di dalam app winscp kita login menggunakan, hostname:ip server, user name: nama server, kemudian klik login dan masukan password server.
8. copy file html kita ke folder arez(serverkita) dengan sistem darg and drop
9. kembali ke server di cmd
10. ketik ls untuk cek apakah file html kita sudah di pindah
11. sudo sp -r ~/nama.html/*(untuk memindahkan file.html)
12. cek apakah website sudah berubah menggunakan ip
