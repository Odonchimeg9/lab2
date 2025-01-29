
Admin@DESKTOP-OI5FUJ9 MINGW64 ~
$ cd lab2

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git init
Reinitialized existing Git repository in C:/Users/Admin/lab2/.git/

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ touch 1-madlib-1.py

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ code .

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   1-madlib-1.py
        new file:   jishee2.py


Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git config --global user.name "Odonchimeg9"

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git config --global user.email "odonchimege72gmail.com"

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git config --global user.email "odonchimege7@gmail.com"

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git commit -m "LAB2"
[master c449f2e] LAB2
 2 files changed, 14 insertions(+)
 create mode 100644 1-madlib-1.py
 create mode 100644 jishee2.py

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git remote add origin https://github.com/Odonchimeg9/lab2.git
error: remote origin already exists.

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git remote -v
origin  https://github.com/Odonchimeg9/lab2.git (fetch)
origin  https://github.com/Odonchimeg9/lab2.git (push)

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git push orrigin master
fatal: 'orrigin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Admin@DESKTOP-OI5FUJ9 MINGW64 ~/lab2 (master)
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 615 bytes | 615.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Odonchimeg9/lab2.git
   566d45b..c449f2e  master -> master

