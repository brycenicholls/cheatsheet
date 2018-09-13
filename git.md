## Git commands
---
### Clone a remote repo
`git clone <url>`
### View info about the remote repo
`git remote -v` 

`git branch -a`

### Show changes made to the code
`git diff`

### Steps to publish changes
`git pull origin master`

`git push origin master`

### Branching
`git branch <branch name>`

`git branch` to list the branches

`git checkout <branch name>` will make the branch active

### Push branch to remote repo
`git push -u origin <branch name>`

`git branch -a`

### Merge with master branch
`git checkout master`

`git pull origin master`

`git branch --merged`

`git merge <branch name> `

`git push origin master`

`git branch -d <branch name` to delete local branch

`git push origin --delete <branch name>` to delete the remote branch

### Fix commits sent to the wrong branch

If you commit to the wrong branch by accident, 
1. Run a `git log` to get the commit hash
```
    bnicholls@uac00095 ✓ git log
    commit ca2d7334a370a9eaa178f8968ed26f1572f1fccf (HEAD -> master)
    Author: Bryce Nicholls <bnicholls@ukcloud.com>
    Date:   Thu Sep 13 15:39:57 2018 +0100

        Sending commit to wrong branch  
```
2. Checkout the branch you want to commit to
 

```
    bnicholls@uac00095 ✓ git checkout updates
    Switched to branch 'updates'
```
3. Use *git cherry-pick* to copy the commit over to the desired branch
```

