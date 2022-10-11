# Latihan 1

Muhammad Dikaisa- 312210289

Instalasi GIT

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~
$ git config --global user.name "Muhammad_Dikaisa"

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~
$ git config --global user.email "muhammadikaisa1@gmail.com"

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~
$ cd Labs_Pemrograman
bash: cd: Labs_Pemrograman: No such file or directory

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~
$ cd Labs_Pemrograman/

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman
$ mkdir Latihan1

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman
$ cd Latihan1

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1
$ git init
Initialized empty Git repository in C:/Users/ASUS/Labs_Pemrograman/Latihan1/.git/

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ echo "# Latihan 1" >> README.md

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ cd README.md
bash: cd: README.md: Not a directory

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ nano README.md

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ git commit -m "File Pertama saya"
[master (root-commit) 1078af6] File Pertama saya
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ git remote add origin https://github.com/MuhammadDikaisa/Labpy

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ git remote add origin https://github.com/MuhammadDikaisa/Labpy.git
error: remote origin already exists.

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 237 bytes | 237.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MuhammadDikaisa/Labpy
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ git clone https://github.com/MuhammadDikaisa/Labpy.git
Cloning into 'Labpy'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ nano
.git/      Labpy/     README.md

ASUS@LAPTOP-GRL9QJ4Q MINGW64 ~/Labs_Pemrograman/Latihan1 (master)
$ nano README.md
