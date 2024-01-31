# Belajar Repository GIT
Kali ini saya berkesempatan untuk menggunakan sebuah tool yang penting dalam pengembangan sebuah aplikasi. Saya mengikuti Bootcamp Data Engineer dari Dibimbing dan materi GIT merupakan salah satu assignment tes yang perlu dikerjakan. Sebagai orang awam dengan dunia IT, saya cukup kewalahan dalam mempelajari istilah-istilah yang digunakan sebagai perintah dalam penggunaan tool GIT. Oleh karena itu, dengan berbagai keterbatasan saya akan menceritakan bagaimana penggunaan tool GIT dalam konteks kasus yang lumayan sederhana.
## Instalasi
Untuk melakukan proyek sederhana ini, perlu memiliki Git yang diinstal di komputer. Jika belum, dapat mengunduhnya dari [situs resmi Git](https://git-scm.com/downloads). Selain itu, perlu juga memiliki akun github dimana merupakan versi GIT yang berbasis online untuk lebih jelasnya bisa mengunjungi (https://github.com/). Pada proyek ini, karena memerlukan bahasa pemograman python, saya mencoba memanfaatkan Miniconda yang merupakan versi mini dari Anaconda sebagai salah paket environtment yang membantu dalam pengembangan yang berbasis python. 
## Buat Repository di GitHub
1. Buka browser dan kunjugi GitHub.
2. Login ke akun GitHub .
3. Klik tombol "+" di pojok kanan atas, kemudian pilih "New repository".
4. Beri nama repository "dibimbing-belajar-github".
5. Klik tombol "Create repository".

Pada tahapan pertama, repository github "dibimbing-belajar-github" sepertinya sudah berhasil dibuat. Dari repository ini, dilakukan tahapan kloning yang secara awam saya artikan sebagai proses repository di github dibawa ke lokal komputer untuk bisa berinteraksi satu sama lain. Untuk melakukan kloning pada github, perlu beberapa tahapan yang perlu dilakukan dimana untuk lebih jelasnya bisa dipelajari pada (https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository). Pada kali ini, saya akan menampilkan proses  singkat untuk melakukan kloning repositori yang sudah saya buat pada akun github.

![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/e56658bc-1bde-4016-9255-e62f13ef99fb)


## Clone Repository
Untuk melakukan clone repository, jalankan perintah berikut di terminal:

```bash
git clone https://github.com/ngurahgotama/dibimbing-belajar-github.git
```
![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/de98af82-9755-4885-a35c-208986536a69)

Pada tambilan gambar diatas menunjukan bahwa sudah berhasil melakukan kloning repository ke komputer local. Tahapan selanjutnya adalah mencoba untuk mengunjungi repository hasil kloningan di komputer local dan menambahkan file berformat CSV sebagai data dalam latihan ini. 


## Buat file Python
1. Masuk ke direktori repository yang sudah di-clone.
2. Download file.csv yang akan digunakan sebagai data.


## Commit Pertama
1. Melakukan commit untuk pertama kali sebagai main/master ke github
```bash
  git push origin master
  ```
2. Melakukan pemeriksaan untuk menampilkan branch main/master

![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/982890c6-c244-42a7-9218-a735b5abcd44)


## Buat Branch Baru
1. Di terminal, masuk ke direktori repository.
2. Ketik perintah berikut untuk membuat branch baru dengan feature:
```bash
  git branch feature
  ```
![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/8bf4a443-093f-4f45-97a0-b0173aa331cc)

3. Buat file Python baru (misalnya, read.py) dan tambahkan function untuk membaca file CSV.

![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/f6de2cb8-f8eb-4f98-aa88-4f282b184eaa)

4. Aktifkan branch baru dengan perintah berikut:
```bash
  git checkout feature
  ```
![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/083a057c-4a8a-4dd0-8eaa-a258b614ad4d)

## Commit dan Push
1. Tambahkan file yang sudah dibuat ke staging area dengan perintah:
```bash
  git add read.py
  ```
![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/82e8e5b5-26aa-47e3-8334-7351012ea1b0)

2. Lakukan commit dengan perintah:

![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/4408633f-45db-49e5-90d4-8d633f030033)

3. Lakukan push ke repository dengan perintah:

![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/6244993e-2644-4437-b687-da9fce602420)

## Buat Pull Request di GitHub
1. Buka browser dan pergi ke repository GitHub.
2. Pilih tab "Compare and Pull requests".

![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/1e8b5d5e-8436-4153-8ef0-0dacb584d0dd)


3. Tampilan akan sebagai berikut:
   
![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/30f791a8-2eb4-481f-8c17-890312fc151b)

5. Feature terbaru untuk membaca file csv sudah ditambahkan

![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/045043b7-bfa2-4089-8b0f-d07aeae26d17)

6. Dokumentasi dari latihan ini menggunakan README dimana file dibuat pada github. Agar file tersebut juga tersipan pada local komputer perlu melakukan metode pull request. Pertama aktifkan brach utama dengan perintah berikut:
 ```bash
  git checkout main
  ```
7. Setelah brach main aktif, lakukan perintah berikut pada terminal lokal
 ```bash
  git pull
  ```
8. Berikut adalah tampilan dari file readme yang telah berhasil di pull dari github

![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/dca2ab56-ef08-4d39-a89e-02e351954a5a)

   


## Kesimpulan
Dalam latihan ini, kita belajar tentang penggunaan dasar Git dan GitHub. Langkah-langkahnya meliputi membuat repository di GitHub, mengunduhnya ke komputer lokal, membuat perubahan pada file Python, membuat branch baru, melakukan commit dan push, membuka pull request di GitHub, dan menggabungkan perubahan dari branch fitur ke branch master/main. Ini adalah langkah-langkah dasar yang dapat membantu kita memahami cara menggunakan Git dan GitHub untuk mengelola proyek perangkat lunak secara efisien.





