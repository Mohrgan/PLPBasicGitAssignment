
MORHBONZ@BnM MINGW64 ~ (master)
$ cd OneDrive

MORHBONZ@BnM MINGW64 ~/OneDrive (master)
$ cd Desktop

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop (master)
$ mkdir PLPBasicGitAssignment

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop (master)
$ cd PLPBasicGitAssignment

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git init
Initialized empty Git repository in C:/Users/segsa/OneDrive/Desktop/PLPBasicGitA
ssignment/.git/

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/Mohrgan/PLPBasicGitAssignment.git

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ touch README.md

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git add README.md

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ code .

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        hello.txt


MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git add hello.txt

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git commit -m "Add hello.txt with a greeting"
[master (root-commit) c4e1a06] Add hello.txt with a greeting
 2 files changed, 1 insertion(+)
 create mode 100644 README.md
 create mode 100644 hello.txt

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git status
On branch master
nothing to commit, working tree clean

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Mohrgan/PLPBasicGitAssign
ment.git'

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$ git push -u origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 282 bytes | 282.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Mohrgan/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

MORHBONZ@BnM MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (master)
$
