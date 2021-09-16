
Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (master)
$ git add .

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (master)
$ git commit -m "first part"
[master (root-commit) a8b25ee] first part
 7 files changed, 864 insertions(+)
 create mode 100644 code/Cell.cpp
 create mode 100644 code/Cell.h
 create mode 100644 code/Field.cpp
 create mode 100644 code/Field.h
 create mode 100644 code/Ship.cpp
 create mode 100644 code/Ship.h
 create mode 100644 code/Source.cpp

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (master)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 6 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (10/10), 4.63 KiB | 1.54 MiB/s, done.
Total 10 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Eto322/Homework-git.git
 * [new branch]      master -> master

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (master)
$ git branch second_part

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (master)
$ git checkout second_part
Switched to branch 'second_part'

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$ git statys
git: 'statys' is not a git command. See 'git --help'.

The most similar command is
        status

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$ git status
On branch second_part
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Sea Battle.exe
        openal32.dll
        resourse/
        sfml-graphics-2.dll
        sfml-system-2.dll
        sfml-window-2.dll

nothing added to commit but untracked files present (use "git add" to track)

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$ git add .

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$ git commit -m "second part"
[second_part 0bdc90a] second part
 10 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Sea Battle.exe
 create mode 100644 openal32.dll
 create mode 100644 resourse/background.jpg
 create mode 100644 resourse/fire.png
 create mode 100644 resourse/miss.png
 create mode 100644 resourse/ship.png
 create mode 100644 resourse/water.png
 create mode 100644 sfml-graphics-2.dll
 create mode 100644 sfml-system-2.dll
 create mode 100644 sfml-window-2.dll

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$ git push
fatal: The current branch second_part has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin second_part


Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$ -set-upstream origin second_part
bash: -set-upstream: command not found

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$  git push --set-upstream origin second_part

Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 6 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (13/13), 1.11 MiB | 6.07 MiB/s, done.
Total 13 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'second_part' on GitHub by visiting:
remote:      https://github.com/Eto322/Homework-git/pull/new/second_part
remote:
To github.com:Eto322/Homework-git.git
 * [new branch]      second_part -> second_part
Branch 'second_part' set up to track remote branch 'second_part' from 'origin'.

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (second_part)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.



Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (master)
$ git merge --no-ff -m "merge second part" second_part
Merge made by the 'recursive' strategy.
 Sea Battle.exe          | Bin 0 -> 27648 bytes
 openal32.dll            | Bin 0 -> 669696 bytes
 resourse/background.jpg | Bin 0 -> 118173 bytes
 resourse/fire.png       | Bin 0 -> 165587 bytes
 resourse/miss.png       | Bin 0 -> 1216 bytes
 resourse/ship.png       | Bin 0 -> 4473 bytes
 resourse/water.png      | Bin 0 -> 19671 bytes
 sfml-graphics-2.dll     | Bin 0 -> 811520 bytes
 sfml-system-2.dll       | Bin 0 -> 50176 bytes
 sfml-window-2.dll       | Bin 0 -> 123392 bytes
 10 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Sea Battle.exe
 create mode 100644 openal32.dll
 create mode 100644 resourse/background.jpg
 create mode 100644 resourse/fire.png
 create mode 100644 resourse/miss.png
 create mode 100644 resourse/ship.png
 create mode 100644 resourse/water.png
 create mode 100644 sfml-graphics-2.dll
 create mode 100644 sfml-system-2.dll
 create mode 100644 sfml-window-2.dll

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (master)
$ git push
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 213 bytes | 213.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Eto322/Homework-git.git
   a8b25ee..9c536af  master -> master

Alejik228@DESKTOP-B0DE5D8 MINGW64 /d/Homework-git (master)
$
