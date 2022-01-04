# **Cara Install Git  dan Cara Menggunakan Git**
[![instagram](https://img.shields.io/badge/Nama-Maulana%20Reza-blue.svg)](https://www.instagram.com/rezastein_) [![instagram](https://img.shields.io/badge/Nim-312110510-blue.svg)](https://www.instagram.com/rezastein_) [![instagram](https://img.shields.io/badge/Kelas-TI.21.C5-blue.svg)](https://www.instagram.com/rezastein_)

### **MY SOSIAL MEDIA :**

[![instagram](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/30px-Instagram_logo_2016.svg.png)](https://www.instagram.com/rezastein_) <br> [![facebook](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/F_icon.svg/30px-F_icon.svg.png)](https://www.facebook.com/rezastein.rezastein) <br> [![twiter](https://upload.wikimedia.org/wikipedia/de/thumb/9/9f/Twitter_bird_logo_2012.svg/30px-Twitter_bird_logo_2012.svg.png)](https://twitter.com/rezastein_) <br> [![whatapp](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/30px-WhatsApp.svg.png)](https://wa.me/qr/UK5NMG54XWHJC1)



## **Install Git**
Instalasi Git di Windows memang tidak seperti di Linux yang ketik perintah langsung terinstal.
Kita harus men-download dulu, kemudian melakukan ritual next>next>finish.

### **Download Git**
Silahkan buka website resminya Git : https://git-scm.com/


klik kanan dan run as administrator file instaler Git yang sudah diunduh.

![.](ScreenShot/1.jpg)
Maka akan muncul infomasi lisensi Git, klik Next > untuk melanjutkan.
![.](ScreenShot/2.jpg)
Selanjutnya menentukan lokasi instalasi. Biarkan saja apa adanya, kemudian klik Next >> sampai muncul sebagai berikut:

Selanjutnya pemilihan emulator terminal. Pilih saja yang bawah, kemudian klik Next >.
![.](ScreenShot/12.jpg)
Setelah selesai, kita bisa langsung klik Finish.
![.](ScreenShot/17.jpg)

Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah 
```sh
git --version
```
![.](ScreenShot/18.jpg)
# **Cara penggunaan Git**

Setelah berhasil install ke Git, selanjutnya
## **Login Git**

masukkan username & email Git menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.

```sh
git config --global user.name "Rezastein"
git config --global user.email rezastein531@gmail.com
```
Selanjutnya untuk memastikan proses login berhasil, masukkan perintah berikut.
```sh
git config --list
```

![.](ScreenShot/19.jpg)

## **Login Github**
Langkah kedua menggunakan Git adalah harus login ke dalam website GitHub. Github dan Git memiliki hubungan khusus, yaitu Git yang berperan sebagai version control system dan Github menjadi hosting atau sebagai penyimpan kode pemrograman.

![.](ScreenShot/21.jpg)


## **Buat Repository**
Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.
![.](ScreenShot/22.jpg)

Kemudian akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.
perlu mengisi detail informasi berikut:

```Nama Repository``` : digunakan untuk identitas repository yang dibuat.
<br>
```Deskripsi Repository``` : berfungsi untuk deskripsi dari repository yang dibuat.
<br>
```Jenis Repository```   : jenis repository  dibagi menjadi Public dan Private. Ketika Anda mengatur repository menjadi Public, orang lain dapat melihat repository yang Anda buat. Sebaliknya, jika Anda mengaturnya sebagai Private, repository tersebut hanya bisa diakses oleh Anda.
Setelah mengisi detail informasi di atas, 
<br>
klik ```Create Repository```.

## **Buat Folder pada Windows**
Selanjutnya, perlu membuat folder pada local disk komputer. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah di buat.
![.](ScreenShot/23.jpg)
## **Buka Folder Menggunakan Git Bash**
![.](ScreenShot/24.jpg)
Setelah berhasil membuat folder pada local disk komputer,  buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. 
![.](ScreenShot/25.jpg)
## **Ubah Folder Menjadi Repository**
Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:
```sh
git init
```
![.](ScreenShot/26.jpg)

## **Tambahkan File ke Repository**
Untuk bisa menambahkan file ke repository GitHub,perlu menerapkan langkah-langkah di bawah ini:

Buat file di folder yang sudah dibuat (Eza-Git). Contohnya, di sini  membuat file javascript : index.php
Buka GitBash lalu masukkan perintah berikut:
```
git add index.php
```
Perintah tersebut tidak akan menghasilkan output apa pun.

## **Buat Commit**
Selanjutnya, perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:
```sh
git commit -m "first commit"
```
bebas membuat membuat nama Commit apa saja.
![.](ScreenShot/27.jpg)

## **Remote Repository Github**
Remote repository berfungsi untuk mengupload file yang telah di buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository:
```sh
git branch -M main
git remote add origin https://github.com/Rezastein/Eza-Git.git
```
Perintah di atas tidak akan menghasilkan output apa pun.

## **Push ke GitHub**
Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub:
```sh
git push -u origin main
```
Perintah di atas akan menampilkan pop up sign in GitHub.
<br>
login untuk melanjutkan proses push ke GitHub. 
<p>
Jika proses login berhasil, akan muncul tampilan Command Prompt seperti di bawah:

![.](ScreenShot/28.jpg)

## **Cek File**
Setelah itu, cek repository yang telah di buat. akan mendapati file-file yang telah ditambahkan sebelumnya. Pada tutorial ini kami menambahkan tiga file, yaitu index.php, ScreenShot/, dan README.md. 

![.](ScreenShot/30.jpg)


## **Kesimpulan**
Cara menggunakan Git ini wajib diketahui dan dikuasai oleh semua developer karena akan sangat membantu dalam mengerjakan project pembuatan website. Demikian penjelasan tentang cara menggunakan Git. Jika masih ada pertanyaan, jangan sungkan untuk meninggalkan di kolom komentar. Jangan lupa juga subscribe untuk mendapatkan informasi terbaru dari kami.



