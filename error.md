PS C:\Users\hrite\Desktop\Rhabdom-1> git commit -m "new"
fatal: Unable to create 'C:/Users/hrite/Desktop/Rhabdom-1/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.
PS C:\Users\hrite\Desktop\Rhabdom-1> rm .git/index.lock
PS C:\Users\hrite\Desktop\Rhabdom-1> git commit -m "new"
[gittutorial.md e57b2d0] new
 1 file changed, 35 insertions(+)
 create mode 100644 tutorial_4.md
PS C:\Users\hrite\Desktop\Rhabdom-1> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 876 bytes | 876.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/harshitrishav2003/Rhabdom.git
   edf0266..e57b2d0  gittutorial.md -> gittutorial.md
PS C:\Users\hrite\Desktop\Rhabdom-1> 