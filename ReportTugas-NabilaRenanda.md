<h1 align="center"> 📑 FINAL REPORT HASIL ASSIGNMENT PRAKTIKUM METODE KOMPUTASI ACARA 3 </h1>

---

- **Nama**  : Nabila Renanda Salsabila  
- **NIM**   : 24/535005/PA/22695  
 
---

## 📘 Laporan p

Pada pertemuan Minggu ketiga, kita mempelajari dasar-dasar penggunaan **GitHub** dan **Visual Studio Code (VS Code)** serta bagaimana keduanya dapat diintegrasikan untuk mendukung pengembangan perangkat lunak. GitHub merupakan platform berbasis web yang digunakan untuk menyimpan, mengelola, dan berkolaborasi dalam proyek perangkat lunak dengan memanfaatkan sistem *Version Control System (VCS)*. Melalui GitHub, setiap perubahan pada kode dapat dicatat secara terstruktur sehingga memudahkan pengembang dalam melacak riwayat, mengelola versi, serta bekerja sama dengan tim dalam skala yang lebih besar. Sementara itu, Visual Studio Code (VS Code) adalah editor kode ringan dan canggih yang mendukung banyak bahasa pemrograman, dilengkapi dengan *debugger*, terminal bawaan, serta berbagai ekstensi yang dapat memperluas fungsinya. Integrasi antara GitHub dan VS Code memungkinkan pengembang tidak hanya menulis kode, tetapi juga mengelola repositori Git langsung dari dalam editor, termasuk melakukan *commit*, *push*, *pull*, hingga mengelola *issues* dan *pull requests*.

Dalam pembelajaran ini, langkah pertama yang dilakukan adalah **registrasi akun GitHub** menggunakan email pribadi serta penentuan username yang akan menjadi identitas global. Selain itu, pengaturan tampilan antarmuka (*UI color preference*) juga dipelajari untuk menyesuaikan pengalaman penggunaan. Setelah itu, kita belajar menghubungkan GitHub dengan perangkat lokal melalui konfigurasi Git pada terminal VS Code. Konfigurasi awal dilakukan dengan memasukkan perintah untuk mengatur *user.name* dan *user.email*, sehingga setiap aktivitas *commit* dapat tercatat atas nama pengguna yang benar. Pada tahap berikutnya, kita mempelajari cara **membuat repository** di GitHub, kemudian meng-*clone* repository tersebut ke perangkat lokal agar bisa dikelola melalui VS Code.

Setelah repository siap, kita mendalami alur kerja dasar version control, yaitu *add → commit → push → pull*. Proses ini dimulai dengan menambahkan file yang telah diedit ke dalam *staging area* menggunakan perintah `git add`, kemudian mencatat perubahan tersebut dengan `git commit` yang disertai pesan deskriptif. Selanjutnya, perubahan dikirimkan ke GitHub menggunakan `git push`, dan apabila ada pembaruan dari repository utama, kita dapat mengambilnya kembali ke perangkat lokal dengan `git pull`. Selain itu, kita juga diajarkan cara mengedit file secara langsung baik melalui GitHub maupun melalui VS Code, termasuk membuat file dokumentasi dengan format Markdown. Dengan Markdown, kita bisa menuliskan laporan atau dokumentasi yang lebih menarik menggunakan heading, teks tebal, miring, tabel, link, hingga gambar.

---

## 💡 Alur Workflow GitHub 

Alur kerja GitHub: 

* **Menyiapkan Folder Proyek**  
  Buat terlebih dahulu sebuah folder di komputer yang akan digunakan untuk menyimpan semua file proyek.

* **Membuka Folder di VS Code**  
  Setelah folder dibuat, buka folder tersebut melalui Visual Studio Code agar semua pengelolaan bisa dilakukan dengan mudah.

* **Inisialisasi Repository Git**  
  Jalankan perintah `git init` di terminal untuk menjadikan folder tersebut sebagai repository lokal. Git akan menambahkan pengaturan internal yang berfungsi menyimpan riwayat perubahan.

* **Menambahkan Remote Repository**  
  Hubungkan repository lokal dengan repository yang ada di GitHub menggunakan perintah:  

* **Melihat Status File**  
  Gunakan `git status` untuk memeriksa file yang baru ditambahkan, diubah, atau siap dicatat oleh Git.

* **Menambahkan File ke Staging Area**  
  File yang ingin disimpan perlu dimasukkan ke staging area terlebih dahulu:  

  * `git add nama_file` untuk menambahkan satu file.  
  * `git add .` untuk menambahkan semua perubahan sekaligus.  

* **Membuat Commit**  
  Jalankan `git commit -m "pesan perubahan"` untuk menyimpan snapshot perubahan ke repository lokal dengan pesan singkat sebagai catatan.

* **Mengatur Branch Utama**  
  Pastikan branch utama memiliki nama `main` dengan perintah `git branch -M main`.

* **Mengirim Perubahan ke GitHub**  
  Gunakan `git push -u origin main` agar commit dari repository lokal terkirim ke repository GitHub dan tersimpan secara online.

* **Mengambil Perubahan dari GitHub**  
  Jika ada pembaruan di GitHub, jalankan `git pull` untuk menyalin perubahan tersebut ke repository lokal.

* **Siklus Kerja Harian**  
  Proses kerja biasanya berulang: mengedit file → memeriksa status → menambahkan file → membuat commit → mengirim ke GitHub. Dengan alur ini, setiap perubahan terdokumentasi rapi dan tetap sinkron antara lokal dan GitHub.

---

## 📌 Kesimpulan
Dari keseluruhan materi, saya belajar bahwa GitHub tidak hanya berfungsi sebagai penyimpanan kode, tetapi juga sebagai media kolaborasi yang efisien. VS Code pun tidak sebatas editor, melainkan juga alat yang terintegrasi dengan Git sehingga mendukung manajemen kode secara langsung. Pemahaman mengenai workflow dasar sangat penting karena menjadi pondasi dalam pengelolaan proyek perangkat lunak. Meskipun demikian, masih terdapat hal-hal yang perlu diperdalam, seperti penggunaan *branch* untuk mengembangkan fitur baru secara terpisah, pengajuan *pull request* untuk kolaborasi tim, serta pengelolaan *issues* sebagai pencatatan bug maupun ide pengembangan.
