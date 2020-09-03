1.
git version 2.28.0.windows.1

2.
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
core.editor="C:\Users\Montana\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
user.name=Montana Stake
user.email=ms053215@ohio.edu

3.
It provides commonly used git command and how they can be used along with how to use git --help

4.
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

5.
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

6.
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

7.
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

PS C:\Users\Montana\Desktop\cs2400\git-lab> git commit -m "Initial commit"
[master (root-commit) b0ec7fd] Initial commit
 2 files changed, 2 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md

8.
commit b0ec7fd79556e73baa71f0fdb9dd4c8186e83293 (HEAD -> master)
Author: Montana Stake <ms053215@ohio.edu>
Date:   Thu Sep 3 12:36:47 2020 -0400

    Initial commit

9.
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

10.
No the changes were not made

11.
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/MontanaStake/git-lab.git'        
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12.
Yes the changes were made

13.
Directory: C:\Users\Montana\Desktop\cs2400\git-lab-2


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----         9/3/2020   3:27 PM            302 .gitignore
-a----         9/3/2020   3:27 PM             11 README.md

