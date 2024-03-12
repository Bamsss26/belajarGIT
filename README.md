Daftar tugas / branch 
  1. Tugas-git
  2. Tugas-html
  3. Tugas-css
  4. Tugas-js
  5. Tugas-midProject
  6. Tugas-php
  7. Tugas-finalProject

Daftar perintah GIT

Costumer@GameBot MINGW64 /d/GIT
$ git clone https://github.com/Bamsss26/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (1/1), done.

Costumer@GameBot MINGW64 /d/GIT
$ git add /d/GIT/belajarGIT/Tugas-Git.txt
fatal: not a git repository (or any of the parent directories): .git

Costumer@GameBot MINGW64 /d/GIT
$ git add /d/GIT/belajarGIT/Tugas-git.txt
fatal: not a git repository (or any of the parent directories): .git

Costumer@GameBot MINGW64 /d/GIT
$ ^C

Costumer@GameBot MINGW64 /d/GIT
$

Costumer@GameBot MINGW64 /d/GIT
$ git add /d/GIT/belajarGIT/Tugas-git.txt
fatal: not a git repository (or any of the parent directories): .git

Costumer@GameBot MINGW64 /d/GIT
$ git init
Initialized empty Git repository in D:/GIT/.git/

Costumer@GameBot MINGW64 /d/GIT (master)
$ cd belajarGIT

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-git

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "tumbelabraham@gmail.com"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "Bamsss26"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugas-git"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Costumer@GameBot.(none)')

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "tumbelabraham@gmail.com"
Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "Costumer@GameBot"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugas-git"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Costumer@GameBot.(none)')

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "tumbelabraham@gmail.com"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "Bamsss26"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugas-git"
[Tugas-git 96f4dbf] tugas-git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Costumer@GameBot MINGW64 /d/GIT/belajarGIT
$ git merge Tugas-git
Updating c76278e..96f4dbf
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 282 bytes | 56.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Bamsss26/belajarGIT.git
   c76278e..96f4dbf  main -> main

