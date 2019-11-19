---

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown
$ git --version
git version 2.24.0.windows.2

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown
$ git init
Initialized empty Git repository in C:/Users/mdala/Desktop/markdown/.git/

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown (master)
$ touch bmd.md

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bmd.md

nothing added to commit but untracked files present (use "git add" to track)

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown (master)
$ git add .

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   bmd.md


mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown (master)
$ git commit -am 'markdown'
[master (root-commit) a46bcbd] markdown
 1 file changed, 78 insertions(+)
 create mode 100644 bmd.md

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown (master)
$ git remote add origin https://github.com/mnhill/markdown.git

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 607 bytes | 607.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/mnhill/markdown.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

mdala@DESKTOP-125MBG8 MINGW64 ~/Desktop/markdown (master)

___