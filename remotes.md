# Git remotes

### List all the remotes
`git remote -v`


### add a remote 
`git remote add origin remote-url.git`

### push changes from local to remote
`git push origin master`


### Fetch -> download changes which are not present locally from the remote
1. `git fetch origin <branch-name>`

2. Merge the updated changes to your local branch
`git checkout master`
`git merge origin/master`

    (or)
 ### Pull -> fetch + merge
 `git pull origin <branch_name>


### Changes made by Dev-B

 
