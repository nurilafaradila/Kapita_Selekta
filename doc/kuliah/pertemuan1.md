**TUTORIAL ADD SSH KEY, BUAT REPOSITORY, PULL DAN PUSH MENGGUNAKAN GITBASH**



1. **Latar Belakang**

- --Cara menambahkan SSH Key.
- --Cara membuat repository baru.
- --Cara pull dan push request.

2. **Pembahasan**

Github adalah server repository untuk git.

Cara Add  SSH Key :

1. Login ke akun github masing-masing.
2. Masuk ke halaman Setting. Pilih SSH dan GPG keys. Klik new SSH key.
3. Pilih generating SSH Keys.
4. Jalankan Git Bash, ketik ssh-keygen -t rsa -b 4096 -C &quot; [your\_email@example.com](mailto:your_email@example.com)&quot; (untuk email, ganti menjadi email github masing-masing). Kemudian enter.
5. Tuliskan cat ~/.ssh/id\_rsa.pub. jika hasilnya muncul copy key ssh tersebut ke ssh bary yang akan di buat.
6. Klik Add SSH Key. Maka proses add SSH key berhasil.

Cara Buat Repository Baru :

1. Login ke akun github masing-masing.
2. Klik ikon + (tambah) dan pilih New repository.
3. Isi nama repository dan deskripsinya.
4. Pilih public dan beri ceklis pada _initialize this repository with a README_, lalu add license.
5. Klik Create repository. Maka proses membuat repository baru berhasil.

Cara Pull and Push Request :

1. Terlebih dahulu buat folder, kemudian klik kanan dan pilih Git Bash Here.
2. Tulis git init untuk penginisialisasian.
3. Tulis git remote add origin dan masukkan link clone repository github.
4. Tulis git pull origin master untuk menarik repository ke dalam folder yang telah dibuat sebelumnya.
5. Buat folder doc/kuliah yang didalamnya terdapat file yang berbentuk .md.
6. Cek status git dengan menuliskan git status.
7. Tulis add doc/kuliah/pertemuan1.md untuk menambahkan file .md ke github.
8. Tulis git commit –m &quot;komentar&quot;.
9. Tulis git push origin master untuk mengupload file ke dalam repository. Maka proses pull dan push request berhasil.



1. **Penutup**

Kesimpulan

Tutorial ini membantu kita untuk mengetahui cara add ssh key, membuat repository baru, dan cara pull push request menggunakan github. Sebenarnya menggunakan github sangatlah mudah dan membantu pekerjaan kita.

Saran

Sebaiknya mencari sumber-sember yang lainnya untuk mengetahui penggunaan git bash lebih baik



Link Github :

Nama        : Nurila Faradila Irfan

NPM        : 1144121

Kelas        : 3A

Prodi        : D4 Teknik Informatika

Kampus        : Politeknik Pos Indonesia

Link Matakuliah : [http://kampus.awangga.net/assignments/kapitaselekta2016](http://kampus.awangga.net/assignments/kapitaselekta2016)

Referensi : [http://kampus.awangga.net/classroom-news/standarpenggunaangit](http://kampus.awangga.net/classroom-news/standarpenggunaangit)

Scan Plagiarisme :

[https://drive.google.com/open?id=0B34z3XSvW4dDbER0MXpIa0ZraVE](https://drive.google.com/open?id=0B34z3XSvW4dDbER0MXpIa0ZraVE)

[https://drive.google.com/open?id=0B34z3XSvW4dDLXltRC04RUs4U2M](https://drive.google.com/open?id=0B34z3XSvW4dDLXltRC04RUs4U2M)