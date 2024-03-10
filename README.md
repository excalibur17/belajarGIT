Daftar tugas/branch
  1.Tugas-git
  2.Tugas-html
  3.Tugas-css
  4.Tugas-js
  5.Tugas-midProject
  6.Tugas-php
  7.Tugas-finalProject

Daftar perintah Git

USER@MSI MINGW64 ~
$ cd D:\Arthur\SEMESTER 4\pemroweb
bash: cd: too many arguments

USER@MSI MINGW64 ~
$ cd "D:\Arthur\SEMESTER 4\pemroweb"

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb
$ git clone https://github.com/excalibur17/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 13 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (13/13), 4.53 KiB | 1.51 MiB/s, done.

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb
$ cd belajarGIT

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git 36c587f] Menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git merge Tugas-git
Updating e8c8ca0..36c587f
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/excalibur17/belajarGIT
   e8c8ca0..36c587f  main -> main

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html 2c02b65] Menambahkan Tugas-Html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git merge Tugas-html
Updating 36c587f..2c02b65
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 293 bytes | 293.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/excalibur17/belajarGIT
   36c587f..2c02b65  main -> main

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-css 4dc92b1] Menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git merge Tugas-css
Updating 2c02b65..4dc92b1
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 246 bytes | 246.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/excalibur17/belajarGIT
   2c02b65..4dc92b1  main -> main

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-js 9aafb5e] Menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git merge Tugas-js
Updating 4dc92b1..9aafb5e
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 246 bytes | 246.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/excalibur17/belajarGIT
   4dc92b1..9aafb5e  main -> main

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-MidProject.txt"
[Tugas-midProject 19baa31] Menambahkan Tugas-MidProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git merge Tugas-midProject
Updating 9aafb5e..19baa31
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 261 bytes | 261.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/excalibur17/belajarGIT
   9aafb5e..19baa31  main -> main

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php 2debaa4] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git merge Tugas-php
Updating 19baa31..2debaa4
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 249 bytes | 249.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/excalibur17/belajarGIT
   19baa31..2debaa4  main -> main

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject f101786] Menambahkan Tugas-FinalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 2debaa4..f101786
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 267 bytes | 267.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/excalibur17/belajarGIT
   2debaa4..f101786  main -> main

USER@MSI MINGW64 /d/Arthur/SEMESTER 4/pemroweb/belajarGIT (main)
$
