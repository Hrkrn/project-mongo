Microsoft Windows [Version 10.0.22631.3296]
(c) Microsoft Corporation. All rights reserved.

C:\Users\user>cd C:\Users\user\Downloads\mongo

C:\Users\user\Downloads\mongo>git init
Reinitialized existing Git repository in C:/Users/user/Downloads/mongo/.git/

C:\Users\user\Downloads\mongo>git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme .MD

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\user\Downloads\mongo>git add .

C:\Users\user\Downloads\mongo>git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme .MD


C:\Users\user\Downloads\mongo>git commit -m "hi everyone, i have created a project description file"
[main (root-commit) ac38869] hi everyone, i have created a project description file
 1 file changed, 65 insertions(+)
 create mode 100644 readme .MD

C:\Users\user\Downloads\mongo>git branch -M main

C:\Users\user\Downloads\mongo>git remote add origin https://github.com/Hrkrn/project-mongo.git
error: remote origin already exists.

C:\Users\user\Downloads\mongo>git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.32 KiB | 676.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Hrkrn/project-mongo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

C:\Users\user\Downloads\mongo>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.MD

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\user\Downloads\mongo>git add .

C:\Users\user\Downloads\mongo>git commit -m "hi everyone, i have created another project description file"
[main 85b8c42] hi everyone, i have created another project description file
 1 file changed, 65 insertions(+)
 create mode 100644 readme.MD

C:\Users\user\Downloads\mongo>git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 295 bytes | 295.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Hrkrn/project-mongo.git
   ac38869..85b8c42  main -> main
branch 'main' set up to track 'origin/main'.

C:\Users\user\Downloads\mongo>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.MD

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\user\Downloads\mongo>git add .

C:\Users\user\Downloads\mongo>git commit -m "hi everyone, i have edited a project description file"
[main 263bf6e] hi everyone, i have edited a project description file
 1 file changed, 1 insertion(+)

C:\Users\user\Downloads\mongo>git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 375 bytes | 187.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Hrkrn/project-mongo.git
   85b8c42..263bf6e  main -> main
branch 'main' set up to track 'origin/main'.
