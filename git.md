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
    bnicholls@terminal ✓ git log
    commit 43039d95188c82ee60f784ca878cf011ea0ae38c (HEAD -> updates, origin/master, origin/HEAD, master)
    Author: Bryce Nicholls <bnicholls@cloud.com>
    Date:   Thu Sep 13 15:16:18 2018 +0100

        Updated git.md
```
2. Checkout the branch you want to commit to
 

```
    bnicholls@uac00095 ✓ git checkout updates
    Switched to branch 'updates'
```
3. Use git *cherry-pick to *
