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

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-html

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git config --global user.email "tumbelabraham@gmail.com"
Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git config --global user.name "Bamsss26"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git commit -m "tugas-html"
[Tugas-html bb86e38] tugas-html
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-Html
Updating 96f4dbf..bb86e38
Fast-forward
 Tugas-Html.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 308 bytes | 61.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Bamsss26/belajarGIT.git
   96f4dbf..bb86e38  main -> main

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-css

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.email "tumbelabraham@gmail.com"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.name "Bamsss26"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT
$ git commit -m "tugas-css"
On branch Tugas-css
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-css.txt

nothing added to commit but untracked files present (use "git add" to track)

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git commit -m "Tugas-Css"
On branch Tugas-css
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-css.txt

nothing added to commit but untracked files present (use "git add" to track)

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.email "tumbelabraham@gmail.com"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git config --global user.name "Bamsss26"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git commit -m "tugas-css"
[Tugas-css 0b86526] tugas-css
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-Css
Updating bb86e38..0b86526
Fast-forward
 Tugas-Css.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 228 bytes | 57.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Bamsss26/belajarGIT.git
   bb86e38..0b86526  main -> main

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-js

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.email "tumbelabraham@gmail.com"
Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git config --global user.name "Bamsss26"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git commit -m "tugas-js"
[Tugas-js 4ae085f] tugas-js
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Js.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-Js
Updating 0b86526..4ae085f
Fast-forward
 Tugas-Js.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Js.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 253 bytes | 50.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Bamsss26/belajarGIT.git
   0b86526..4ae085f  main -> main

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-midproject

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-midprojec
error: pathspec 'Tugas-midprojec' did not match any file(s) known to git

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "tumbelabraham@gmail.com"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.name "Bamsss26"
Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "tugas-midproject"
[Tugas-midProject 2f3ffeb] tugas-midproject
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating 4ae085f..2f3ffeb
Fast-forward
 Tugas-midProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 242 bytes | 80.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Bamsss26/belajarGIT.git
   4ae085f..2f3ffeb  main -> main

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-php

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git config --global user.email "tumbelabraham@gmail.com"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git config --global user.name "Bamsss26"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugas-php"
[Tugas-php 01bf7f2] tugas-php
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-Php
Updating 2f3ffeb..01bf7f2
Fast-forward
 Tugas-Php.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 225 bytes | 56.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Bamsss26/belajarGIT.git
   2f3ffeb..01bf7f2  main -> main

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-finalProject

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.email "tumbelabraham@gmail.com"
Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.name "Bamsss26"

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "tugas-finalproject"
[Tugas-finalProject a98e48c] tugas-finalproject
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 01bf7f2..a98e48c
Fast-forward
 Tugas-finalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 245 bytes | 61.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Bamsss26/belajarGIT.git
   01bf7f2..a98e48c  main -> main

Costumer@GameBot MINGW64 /d/GIT/belajarGIT (main)
$
