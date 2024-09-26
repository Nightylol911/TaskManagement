```diff
 ## 1 TaskManagement Project
- Initialize the .git folder using the command !(git init)
- Create the README.md file using the command !(echo "file name")
- Added the file README.md to the stage sing the command !(git add "file name")
- Commit the file using the command !(commit -m "message")
- Renaming the Master branch into main using !(branch -M main)
- cConnect to the repo using command !(remote add origion "repo link")
- Push the changes to the remote repo using !(push -u origion main)

## 2
- making tasks.txt using touch command then staging using !(add .) then commit the changes
- push the above changes to make the repo up to date as local

## 3
- using !(git checkout -b "branch name") to create and move to the new branch
- add lines to the tasks.txt and commit as done before
- switch to main !(git checkout main) and merge the newly created branch using !(git merge "new branch")

## 4 
- create new branch named "feature/remove-tasks" using the command !(git checkout -b feature/remove-tasks)
- after deleting some lines from the tasks.txt stage those changes and commit them as before
- moving to the main branch using the command !(git checkout main)
- then merging the newly created branch as done before (no conflicts accord)

## 5
- same as done before create new branch called "feature/update-tasks"
- update the tasks.txt and stage the changes then committed them using !(add . / commit -m "message")
- moving to the main branch as done before then rebasing using !(git rebase feature/update-tasks)

## 6
- hard resetting the commit included wrong lines using the commit SHA id with this command !(git reset --hard "commit id")
- pushing the changes to the repo using !(git push -f) for force pushing

## 7 Must used git commands
- git status, add ., commit, push, checkout

## Thanks.
```
