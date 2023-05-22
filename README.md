# learning-git

Starting lesons of git which includes
1. git add -A // to add all the untracked/tracked files into staging area
2. git commit -sm "" // -sm is to signoff and move the staging files into committed area
3. git restore // restores a file or folder to a specific commit
4. git push remote branch // pushes code to the github from local
5. git pull remote branch // pull the code from github to local
6. git add remote git@hostname // linking your local folder with the apt github account  
7. git branch <branch-name> // only create bracnh
8. git checkout <branch-name> // only checkout
9. git checkout -b branchname  // "to create and checkout"
10. git branch -d branchname  // "to delete the branch" 
11. git rebase <remote> <branch>
12. git stash save / pop / apply / list and others // commands related to stash
13. git log --oneline (--color --graph --decorate) // to show logs in one line (along with the journey oif respective branches merged into main branch)
14. git rebase -i <commit-id> // interaitve editor will open to group the commits, you cna even squash the more than one commits into one. This helps to make the merge linear.
  [GIT even allows you to configure whenewver you merge, it automatically gets squashed and merged]
  
