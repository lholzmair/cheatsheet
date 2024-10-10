PS C:\Users\lholz\Desktop\KlonKrieger> cd C:\Users\lholz\Desktop\WMD\cheatsheet
PS C:\Users\lholz\Desktop\WMD\cheatsheet> git init
Initialized empty Git repository in C:/Users/lholz/Desktop/WMD/cheatsheet/.git/
PS C:\Users\lholz\Desktop\WMD\cheatsheet> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        cheatsheet.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\lholz\Desktop\WMD\cheatsheet> git cheatsheet.html
git: 'cheatsheet.html' is not a git command. See 'git --help'.
PS C:\Users\lholz\Desktop\WMD\cheatsheet> git add cheatsheet.html
PS C:\Users\lholz\Desktop\WMD\cheatsheet> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   cheatsheet.html

PS C:\Users\lholz\Desktop\WMD\cheatsheet> git add .
PS C:\Users\lholz\Desktop\WMD\cheatsheet> git commit -m "commit cheatsheet"
[master (root-commit) 8dba42f] commit cheatsheet
 1 file changed, 49 insertions(+)
 create mode 100644 cheatsheet.html
PS C:\Users\lholz\Desktop\WMD\cheatsheet> git remote add origin https://github.com/lholzmair/cheatSheet.git
PS C:\Users\lholz\Desktop\WMD\cheatsheet> git branch -M main
PS C:\Users\lholz\Desktop\WMD\cheatsheet> git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1014 bytes | 1014.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/lholzmair/cheatSheet.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\lholz\Desktop\WMD\cheatsheet>