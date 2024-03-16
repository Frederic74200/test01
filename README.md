# test01
Test01


Windows PowerShell
Copyright (C) Microsoft Corporation. Tous droits réservés.

Testez le nouveau système multiplateforme PowerShell https://aka.ms/pscore6

PS C:\Users\fredd> cd .\Documents\
PS C:\Users\fredd\Documents>
PS C:\Users\fredd\Documents>
PS C:\Users\fredd\Documents> cd .\TestGit\
PS C:\Users\fredd\Documents\TestGit> git clone https://github.com/Frederic74200/test01.git
Cloning into 'test01'...
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (5/5), 4.45 KiB | 506.00 KiB/s, done.
PS C:\Users\fredd\Documents\TestGit> git branch
fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\fredd\Documents\TestGit> cd .\test01\
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01> git branch
* main
PS C:\Users\fredd\Documents\TestGit\test01> git branch develop
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01> git branch
  develop
* main
PS C:\Users\fredd\Documents\TestGit\test01> git checkout develop
Switched to branch 'develop'
PS C:\Users\fredd\Documents\TestGit\test01> git branch
* develop
  main
PS C:\Users\fredd\Documents\TestGit\test01> git merge main
Already up to date.
PS C:\Users\fredd\Documents\TestGit\test01> git status
On branch develop
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\fredd\Documents\TestGit\test01> git add *
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01> git status
On branch develop
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

PS C:\Users\fredd\Documents\TestGit\test01> git commit -m "mise à jour du test"
[develop 40b9a75] mise à jour du test
 1 file changed, 14 insertions(+)
 create mode 100644 index.html
PS C:\Users\fredd\Documents\TestGit\test01> git push origin develop
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 460 bytes | 230.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'develop' on GitHub by visiting:
remote:      https://github.com/Frederic74200/test01/pull/new/develop
remote:
To https://github.com/Frederic74200/test01.git
 * [new branch]      develop -> develop
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01> git branch
* develop
  main
PS C:\Users\fredd\Documents\TestGit\test01>
PS C:\Users\fredd\Documents\TestGit\test01> git status
On branch develop
nothing to commit, working tree clean
PS C:\Users\fredd\Documents\TestGit\test01> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\fredd\Documents\TestGit\test01> git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 908 bytes | 302.00 KiB/s, done.
From https://github.com/Frederic74200/test01
   4d688c7..42bc28d  main       -> origin/main
Updating 4d688c7..42bc28d
Fast-forward
 index.html | 14 ++++++++++++++
 1 file changed, 14 insertions(+)
 create mode 100644 index.html
PS C:\Users\fredd\Documents\TestGit\test01>



/////////////////////////////////////////////


PS C:\Users\fredd\Documents\TestGit\DWWM_2304-PHP_votation>
PS C:\Users\fredd\Documents\TestGit\DWWM_2304-PHP_votation>
PS C:\Users\fredd\Documents\TestGit\DWWM_2304-PHP_votation>
PS C:\Users\fredd\Documents\TestGit\DWWM_2304-PHP_votation>
PS C:\Users\fredd\Documents\TestGit\DWWM_2304-PHP_votation> cd ..
PS C:\Users\fredd\Documents\TestGit>
PS C:\Users\fredd\Documents\TestGit> git clone https://github.com/Frederic74200/CDA_2105.git
Cloning into 'CDA_2105'...
remote: Enumerating objects: 1073, done.
remote: Counting objects: 100% (75/75), done.
remote: Compressing objects: 100% (16/16), done.
remote: Total 1073 (delta 62), reused 61 (delta 59), pack-reused 998
Receiving objects: 100% (1073/1073), 7.84 MiB | 13.06 MiB/s, done.
Resolving deltas: 100% (436/436), done.
PS C:\Users\fredd\Documents\TestGit> cd .\CDA_2105\
PS C:\Users\fredd\Documents\TestGit\CDA_2105> git branch develop
PS C:\Users\fredd\Documents\TestGit\CDA_2105> git checkout develop
Switched to branch 'develop'
PS C:\Users\fredd\Documents\TestGit\CDA_2105> git branch
* develop
  main
PS C:\Users\fredd\Documents\TestGit\CDA_2105> git pull origin develop
From https://github.com/Frederic74200/CDA_2105