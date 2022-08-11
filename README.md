PS C:\Users\onjil\Desktop\netflix-project> git remote add origin https://github.com/SheyNjila2021/netflix-project.git
PS C:\Users\onjil\Desktop\netflix-project> git remote -v
origin  https://github.com/SheyNjila2021/netflix-project.git (fetch)
origin  https://github.com/SheyNjila2021/netflix-project.git (push)
PS C:\Users\onjil\Desktop\netflix-project> git pull origin 
You asked to pull from the remote 'origin', but did not specify
a branch. Because this is not the default configured remote
for your current branch, you must specify a branch on the command line.
PS C:\Users\onjil\Desktop\netflix-project> git pull        
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master


PS C:\Users\onjil\Desktop\netflix-project> git push --set-upstream origin master  
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 585 bytes | 195.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/SheyNjila2021/netflix-project.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.