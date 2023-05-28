PS C:\Users\hrite\Desktop\Rhabdom-1> git checkout gittutorial.md
Switched to branch 'gittutorial.md'
M       filenew.md
D       harshit
Your branch is up to date with 'origin/gittutorial.md'.
PS C:\Users\hrite\Desktop\Rhabdom-1> git commit -m "updated"
On branch gittutorial.md
Your branch is up to date with 'origin/gittutorial.md'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   filenew.md
        deleted:    harshit
        modified:   tutorial_2

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\hrite\Desktop\Rhabdom-1> git push
Everything up-to-date
PS C:\Users\hrite\Desktop\Rhabdom-1> git add tutorial_3.md
PS C:\Users\hrite\Desktop\Rhabdom-1> git commit -m "new"
[gittutorial.md edf0266] new
 1 file changed, 30 insertions(+)
 create mode 100644 tutorial_3.md/1.md
PS C:\Users\hrite\Desktop\Rhabdom-1> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 906 bytes | 906.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/harshitrishav2003/Rhabdom.git
   fb323da..edf0266  gittutorial.md -> gittutorial.md
PS C:\Users\hrite\Desktop\Rhabdom-1> 