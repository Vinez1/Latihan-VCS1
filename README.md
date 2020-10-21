# Latihan-VCS1

**Nama : Fery Affandi** <br>

**Nim :  312010018** <br>

**Kelas : TI.20.A.1** <br>

## Langkah-langkah  penggunaan git 

* Download git terlebih dahulu dengan link berikut [click here](https://git-scm.com) <br>

![gitscm](foto/GitBush.png)

* Setelah file terdownload, silahkan instalasi dengan referensi berikut ini : [Git installation guide](https://git-scm.com/book/en/v2/getting-Started-Installing-Git) <br>


![installing](foto/installing.png) <br>

* Setelah instalasi selesai, buka *software* **GitBash** pada menu di windows, dan lakukan pengecekan **versi**, dengan mengetik *syntax* berikut : <br>

`git --version` <br>

![git version](foto/git-version.png) <br>

* Jika muncul tampilan **git version**, berarti Git sudah **Berhasil di install** dan bisa di **gunakan** Langkah pertama kita harus **mengkorfirmasikan user name** dan **email di git**, dengan mengetikkan *syntax* berikut : <br>

`git commit --global user.name "masukan nama anda"` <br>

`git commit --global user.email "masuka email anda"` <br>

![Git Config](foto/gitconfig1.png) <br>

* Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan pemerintah berikut : <br>

`git config --global user.name` <br>

`git config --global user.email` <br>

![GitConfig1](foto/gitconfig2.png) <br>

* Buat akun di **Github**, seperti contoh dibawah ini. Dan lakukan verifikasi melalui akun email yang sudah terdaftar.

* Jika akun **Github** sudah selesai dibuat dan di verifikasi, proses selanjutnya silahkan  buat repository seperti gambar dibawah ini : <br>
**Penjelasan**

> *`Repository Name : (silahkan isi nama repository yang diinginkan seperti contoh saya ingin membuat repository latihan Latihan VCS)`* <br>

> *`Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)`* <br> 

> *`Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)`* <br>

> *`Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda`* <br>

> *`Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.`* <br>

> *`Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan`* <br>

![Nama Repository](foto/Nama-repository.png) <br>

* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini : <br>

![Hasil Repository](foto/Hasil.Repository.png) <br>

* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk me-remote repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link URL git kita di Github, dengan cara tekan tombol Code lalu klik Copy. <br>

![GitLink](foto/code-link.png) <br>

* Setelah Link URL git kita tercopy, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan mendownload Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih Git Bash Here. <br>

![Git Bash](foto/GitBash.png) <br>

* Pop Up Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut :

`git clone [URL] pada contohnya, saya akan memasukan git clone` <br>
https://github.com/Vinez1/Latihan-VCS1.git

![Git Commit](foto/git.commit.png) <br>

*Setelah proses cloning selesai, pada saat ini kita masih pada folder awal (master), kita harus masuk kedalam folder yang telah dicloning tadi yaitu LatihanVCS dengan mengetikkan syntax berikut : <br>

`cd latihan-VCS1/` <br>

![git Cd](foto/cd.png) <br>

* Saat ini kita sudah masuk kedalam folder LatihanVCS, Silahkan edit file README.md yang ada di File Explorer. Bisa menggunakan Text Editor (Sublime Text, Notepad, Notepad++, Visual Studio Code). Edit sesuai dengan keinginan. Aturan file .md (Markdown) bisa dilihat di Link berikut ini : [click here](https://guides.github.com/features/mastering-markdown/) <br>

![README.md](foto/Readme.png) <br>

Setelah file README.md diedit, silahkan Simpan file tersebut dengan cara CTRL+S atau File -> Save <br>

* Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash (CMD). Ketik pada Git Bash seperti berikut ini : <br>

`git add .` <br>

![Git add](foto/git.add.png) <br>

* Setelah selesai melakukan git add . langkah berikutnya kita akan melakukan *commit. Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini : <br>

`git commit "Update README.md"` <br>

![git.commit](foto/git.commit.png) <br>

* Git commit telah selesai di lakukan. Untuk saat ini akan melakuka Git Push, Git Push berfungsi untuk mengirimkan perubahan file setelah di commit ke remote repository. Silahkan ketik pada App Git Bash seperti berikut : <br>

`Git Push` <br>

![GitPush](foto/gitpush.png) <br>

* Semua proses telah selesai, silahkan kembali ke Web Browser untuk melihat perubahan yang telah di commit dan push dari remote. <br>

![Hasil Repository](foto/Hasil.Repository.png) <br>

# Sekian Dari Saya Terima Kasih. <br>

# Fery Affandi