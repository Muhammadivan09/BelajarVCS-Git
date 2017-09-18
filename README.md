# VCS (Version Control System)
Version control adalah sebuah sistem yang mencatat setiap perubahan terhadap sebuah berkas atau kumpulan berkas sehingga pada suatu saat kita dapat kembali kepada salah satu versi dari berkas tersebut.

## Git
Git adalah version control system yang digunakan para developer untuk mengembangkan software secara bersama-bersama. Fungsi utama git yaitu mengatur versi dari source code program anda dengan mengasih tanda baris dan code mana yang ditambah atau diganti.

## GitHub
GitHub adalah layanan yang menggunakan Git sebagai Version Control untuk mengelola dan memanajemen berkas.

## Repository / Repo
Repository adalah sebuah tempat untuk menampung berkas.

## Basic git commands

### git init
```git init``` adalah sebuah perintah untuk menginisialisasi git kedalam berkas project.

### git clone
```git clone [repo_link]``` adalah sebuah perintah untuk mengkloning atau menyalin repository yang ada di internet kedalam komputer.

### git status
```git status``` adalah sebuah perintah untuk melihat status perubahan berkas.

### git log
```git log``` adalah sebuah printah untuk menampilkan informasi tentang commit yang ada.

### git show
```git show``` adalah sebuah perintah untuk menampilkan informasi tentang commit yang diberikan.

### git add
```git add``` adalah sebuah perintah untuk menambahkan berkas dari komputer kedalam git.

### git commit
```git commit``` adalah sebuah perintah untuk memberikan commit atau menandai perubahan pada berkas.

### git diff
```git diff``` adalah sebuah perintah untuk menampilkan perbedaan kedua versi berkas (Setelah perubahan dan sebelum perubahan berkas).

## Tagging, Branching, and Merging

### git tag
```git tag``` adalah sebuah perintah untuk menambahkan label spesifik pada commit yang dapat menunjukan informasi yang berguna. Seperti "Ini adalah rilis beta".

### git branch
```git branch``` adalah sebuah perintah untuk percabangan, dengan fitur percabangan ini memungkinkan developer untuk mengembangkan fitur baru dengan cabang baru tanpa merusak berkas yang sudah ada.

### git checkout
```git checkout``` adalah sebuah perintah untuk beralih diantara cabang-cabang / tag-tag yang berbeda.

### git merge
```git merge``` adalah sebuah perintah untuk menyatukan cabang yang berbeda dan menggabungkan mereka bersama-sama secara otomatis.

## Undoing Changes

### git commit --amend
```git commit --amend``` adalah sebuah perintah yang dilakukan jika lupa menyertakan berkas dalam melakukan atau memiliki kesalahan ketik dalam pesan commit.

### git revert
```git revert [SHA]``` adalah sebuah perintah untuk mengembalikan commit dan barisi yang ditambahkan pada commit sebelumnya akan dihapus.

### git reset
```git reset``` adalah sebuah perintah untuk menghapus commit, perintah ini dapat berpotensi bahaya karena akan menghapus berkas pada repository.

## .gitignore
.gitignore adalah sebuah berkas untuk menandai berkas yang tidak akan dipush ke repository.
