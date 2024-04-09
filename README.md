# PLPBasicGitAssignment
C:\Users\UBF Kenya>cd C:\Users\UBF Kenya\Documents\PLPBasicGitAssignment

C:\Users\UBF Kenya\Documents\PLPBasicGitAssignment>git init
Reinitialized existing Git repository in C:/Users/UBF Kenya/Documents/PLPBasicGitAssignment/.git/

C:\Users\UBF Kenya\Documents\PLPBasicGitAssignment>git remote add origin https://github.com/PeterShako/PLPBasicGitAssignment.git
error: remote origin already exists.

C:\Users\UBF Kenya\Documents\PLPBasicGitAssignment>git add hello.txt

C:\Users\UBF Kenya\Documents\PLPBasicGitAssignment>git commit -m "Add hello.txt with a greeting"
[master 7ce01ad] Add hello.txt with a greeting
 1 file changed, 39 insertions(+)
 create mode 100644 hello.txt

C:\Users\UBF Kenya\Documents\PLPBasicGitAssignment>git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.54 KiB | 786.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/PeterShako/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/PeterShako/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

C:\Users\UBF Kenya\Documents\PLPBasicGitAssignment>
