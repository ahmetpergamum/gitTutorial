# Basic Git Commands

### Show the branch status, if you modify your directory it shows changed files.

`git status`

### Track the changed files
Specify file-name or put a dot to track all files

`git add <file-name or .>`

### Commit the changes with related message

`git commit -m 'message_for_the_changes' `

### Push the changes to the remote git repo

`git push`

## Create a branch
### First checkout from master to a new branch
`git checkout -b <branch-name>`

### Work on your branch and push to the repo
`git push -u origin <branch-name>`

### Authorized person merge the branches
`git merge`

### Checkout from branch to master
`git checkout master`
