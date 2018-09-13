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
1. Run a `git log` to get the commit ID

2. 

