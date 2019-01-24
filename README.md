# Dokumentasi-Git
Mengenal perintah dasar GIT
$ git init -> membuat repositori lokal di dalam folder
$ git clone -> clone atau copy projek dari repositori
$ git status -> menampilkan status pada repositori lokal
$ git add -> menambah file baru pada repositori yang dipilih
$ git commit -> menyimpan perubahan, dan setiap perubahan ini wajib memberikan keterangan pada setiap perubahan
$ git push -> mengirimkan perubahan file setelah di commit ke repositori
$ git pull -> mengambil file yang sudah di ubah dan di upload
$ git branch -> melihat branch yang tersedia pada repositori
$ git merge -> menggabungkan semua branch yang ada pada repositori.

0. Daftar account di https://github.com dan buat repository dengan nama "myproject"
1. Installasi Git
   $ sudo apt install git   
2. Konfigurasi Awal
   $ git config --global user.name "Johan Daeng"
   $ git config --global user.email johan@daeng.net
   $ git config --list
3. Membuat repository di local
   $ mkdir myproject
   $ cd myproject/
   $ git init
4. Buat file dalam directory myproject
   $ touch about.html index.html
   $ git status
5. Menambahkan file project kita ke staged
   $ git add *.html atau
   $ git add *
6. Ubah file projet kita dari staged ke commited
   $ git commit -m "myproject"
7. Remote repository
   $ git remote add origin https://github.com/johandaeng/myproject.git
8. Remove repository lalu pull project kita
   $ git pull origin master atau
   $ git pull origin master --allow-unrelated-histories
9. Mengirim ke repository kita
   $ git push origin master
10. Masukan usernama dan password saat diminta dan tunggu sampai project selesai di upload
11. Cek project kita di github apakah sudah terupload


