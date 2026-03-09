<div align="center">
  <br />

  <h1>LAPORAN PRAKTIKUM <br>
  APLIKASI BERBASIS PLATFORM
  </h1>

  <br />

  <h3>MODUL I <br>
  GIT
  </h3>

  <br />

  <p align="center">
<img src="logo.jpeg" width="200">
</p>

  <br />
  <br />
  <br />

  <h3>Disusun Oleh :</h3>

  <p>
    <strong>Abda Firas Rahman</strong><br>
    <strong>2311102049</strong><br>
    <strong>S1 IF-11-01</strong>
  </p>

  <br />

  <h3>Dosen Pengampu :</h3>

  <p>
    <strong>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</strong>
  </p>
  
  <br />
  <br />
    <h4>Asisten Praktikum :</h4>
    <strong>Apri Pandu Wicaksono </strong> <br>
    <strong>Rangga Pradarrell Fathi</strong>
  <br />

  <h3>LABORATORIUM HIGH PERFORMANCE
 <br>FAKULTAS INFORMATIKA <br>UNIVERSITAS TELKOM PURWOKERTO <br>2026</h3>
</div>

<hr>

## Dasar Teori

### Apa itu Git?

Git adalah sistem version control yang digunakan untuk mengelola dan melacak perubahan pada file atau kode dalam sebuah project. Git membantu developer menyimpan riwayat perubahan sehingga jika terjadi kesalahan kita bisa kembali ke versi sebelumnya. Selain itu Git juga memudahkan banyak orang untuk bekerja pada project yang sama secara bersamaan tanpa takut file saling tertimpa.Dengan Git, setiap perubahan yang dilakukan pada project dapat dicatat melalui proses commit, lalu disimpan di repository baik secara lokal maupun online seperti di GitHub.

### Instalasi Git


Sebelum menggunakan Git, kita perlu melakukan instalasi terlebih dahulu pada komputer. Git dapat diunduh melalui website resminya yaitu https://git-scm.com. Setelah masuk ke website tersebut, pilih tombol download sesuai dengan sistem operasi yang digunakan. Setelah file installer berhasil diunduh, jalankan file tersebut dan ikuti langkah-langkah instalasi sampai selesai. Setelah proses instalasi selesai, Git dapat dicek apakah sudah terpasang dengan benar atau belum melalui Command Prompt atau terminal dengan mengetik perintah: git --version

Screenshot 2026-03-09 193417.png

### Penggunaan Git

Git pada umumnya digunakan untuk version controlling suatu software, berikut list penggunaan github:

#### 1. Membuat repositori baru

Perintah `git init` akan membuat sebuah direktori bernama .git di dalam proyek yang akan dikerjakan. Direktori ini digunakan Git sebagai database untuk menyimpan perubahan yang kita lakukan.

#### 2. Menambahkan isi repositori

Untuk menambahkan suatu file ke dalam repositori, dapat langsung menambahkan file ke dalam folder projek yang telah dibuat, sebelum file benar benar tersimpan harus melakukan command `git commit -m “pesan commit”`.

#### 3. Membuat repositori online

Untuk membuat repositori online dapat dilakukan melalui website github.

#### 4. Menyimpan hasil pekerjaan di repositori online

Untuk menyimpan hasil pekerjaan bisa mengikuti langkah langkah berikut:

- a. Ketikan perintah ini, sesuaikan dengan username dan repository Anda:
`git remote add origin https://github.com/usernameanda/namarepo.git`
Perintah ini akan menambahkan repositori online yang ada pada Github kedalam daftar repositori jarak jauh yang ada.
- b. Untuk mengirimkan data yang ada di komputer kalian ke repositori jarak jauh, gunakan perintah ini:
`git push -u origin master`

#### 5. Clone repositori milik orang lain  

Untuk mengclone repositori orang lain bisa mengikuti langkah langkah berikut:

- a. Buka repositori yang akan di-clone pada Github, lalu klik tombol clone.
- b. Copy text yang muncul seperti dibawah ini, ini merupakan url dari repositori tujuan yang akan di clone.
- c. Buka command prompt dan ketikan perintah ini, `git clone [url repositori tujuan]`

## Tugas

### 1. Melakukan setup repository via CLI

### Output

![Output 1](images/task_image1.png)
Gambar tersebut merupakan proses untuk membuat suatu repositori mulai dari `git init` sampai `git push origin main`. git init merupakan inisialisasi repositori lokal lalu diikuti dengan penambahan file ke repositori, commit, pembuatan branch, clone repositori online lalu yang terakhir push.
![Output 2](images/task_image2.png)
Gambar tersebut merupakan contoh output dari command-command sebelumnya. File berhasil disimpan pada repositori online melalui CLI.
