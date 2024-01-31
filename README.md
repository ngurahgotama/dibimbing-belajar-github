# Assignment Day 3 - GIT
Repository ini dibuat sebagai bagian dari latihan untuk belajar penggunaan Git dan GitHub.
## Instalasi
Untuk menggunakan proyek ini, perlu memiliki Git diinstal di komputer. Jika belum, dapat mengunduhnya dari [situs resmi Git](https://git-scm.com/downloads).
## Buat Repository di GitHub
1. Buka browser dan pergi ke GitHub.
2. Login ke akun GitHub .
3. Klik tombol "+" di pojok kanan atas, kemudian pilih "New repository".
4. Beri nama repository "dibimbing-belajar-github".
5. Klik tombol "Create repository".

![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/e56658bc-1bde-4016-9255-e62f13ef99fb)


## Clone Repository
Untuk melakukan clone repository, jalankan perintah berikut di terminal:

```bash
git clone https://github.com/ngurahgotama/dibimbing-belajar-github.git
```
![image](https://github.com/ngurahgotama/dibimbing-belajar-github/assets/124243915/de98af82-9755-4885-a35c-208986536a69)


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

## Kesimpulan
Dalam latihan ini, kita belajar tentang penggunaan dasar Git dan GitHub. Langkah-langkahnya meliputi membuat repository di GitHub, mengunduhnya ke komputer lokal, membuat perubahan pada file Python, membuat branch baru, melakukan commit dan push, membuka pull request di GitHub, dan menggabungkan perubahan dari branch fitur ke branch master/main. Ini adalah langkah-langkah dasar yang dapat membantu kita memahami cara menggunakan Git dan GitHub untuk mengelola proyek perangkat lunak secara efisien.





