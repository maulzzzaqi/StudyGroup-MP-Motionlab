# Week 1 - Version Control System

## Apa Itu Version Control?
Version control adalah sistem yang biasa digunakan oleh developer untuk mengelola perubahan pada source code. Version control memungkinkan developer untuk melakukan pengecekan terhadap perubahan-perubahan yang terjadi terhadap source code. Adanya version control juga memungkinkan developer untuk melakukan kolaborasi dengan developer lainnya jika dibutuhkan.

## Contoh Version Control
* **Git**\
Git adalah version control yang paling populer dan banyak digunakan oleh developer dalam mengembangkan software. Git memungkinkan developer mengelola perubahan kode. Git juga memungkinkan developer untuk bekerja secara kolaboratif dengan developer lainnya karena fitur _branching_ yang sangat bermanfaat untuk kolaborasi.
* **Github**\
Github adalah platform website yang menggunakan Git. GitHub memfasilitasi kolaborasi tim dengan menyediakan fitur-fitur yang berguna seperti issue tracking, project board, dan code review. Selain Github, tersedia juga platform lain yang mendukung Git seperti Gitlab dan Bitbucket

## Fitur-fitur Git
Beberapa fitur yang penting dan biasa digunakan adalah:

* **Commit**: Berfungsi untuk merekam perubahan sebagai sebuah snapshot dari kode pada momen tertentu.

* **Branching**: Berfungsi untuk menciptakan sebuah cabang kode (branch) agar pengembangan fitur baru tidak mengganggu kode utama.

* **Merging**: Berfungsi untuk menyatukan perubahan dari branch yang berbeda kembali ke branch utama.

* **Revert**: Berfungsi untuk membatalkan perubahan yang sudah telanjur dibuat

* **Stash**: Berfungsi untuk menyimpan perubahan yang sedang dikerjakan (sementara) tanpa perlu melakukan commit.

## Perintah Dasar Git
Beberapa perintah dasar Git yang biasa digunakan adalah:

* ```git init``` : Memulai (menginisialisasi) sebuah repositori baru.

* ```git status``` : Mengecek perubahan yang telah terjadi.

* ```git add```: Memasukkan perubahan ke dalam staging area.

* ```git commit``` : Menyimpan perubahan yang ada di staging area sebagai satu versi.

* ```git push```: Mengirimkan perubahan ke repositori jarak jauh.

* ```git pull```: Menarik pembaruan (update) dari repositori jarak jauh.

* ```git reset```: Kembali ke kondisi commit tertentu, sering dipakai untuk "undo".