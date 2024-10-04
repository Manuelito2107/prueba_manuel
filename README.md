
manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git init
Initialized empty Git repository in C:/Users/manue/OneDrive/Escritorio/prueba_manuel/.git/

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (master)
$ git add .

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (master)
$ git commit -m "prueba_2"
[master (root-commit) 23c0dbb] prueba_2
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 TRABAJO.txt

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (master)
$ giit branch -m main
bash: giit: command not found

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (master)
$ git branch -m main

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git remote add origin https://github.com/Manuelito2107/prueba_manuel.git

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 216 bytes | 216.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Manuelito2107/prueba_manuel.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ ^C

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Trabajo 2.txt

nothing added to commit but untracked files present (use "git add" to track)

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git add Trabajo 2.txt
fatal: pathspec 'Trabajo' did not match any files

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git commin -m "version 2"
git: 'commin' is not a git command. See 'git --help'.

The most similar command is
        commit

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git push -u origin main
Everything up-to-date
branch 'main' set up to track 'origin/main'.

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Trabajo 2.txt

nothing added to commit but untracked files present (use "git add" to track)

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git log
commit 23c0dbbdde25bb2164cc5d8b8a1a1eec892aa74c (HEAD -> main, origin/main)
Author: Manuelito2107 <manuelcalle2107@gmail.com>
Date:   Fri Oct 4 10:06:19 2024 +0200

    prueba_2

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git add .

manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Trabajo 2.txt


manuel@WS_Manuelos21 MINGW64 ~/OneDrive/Escritorio/prueba_manuel (main)
$
