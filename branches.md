# Branches basics


### list branches

`git branch`


### create a new branch
`git branch <new-branch-name>`



### switch between branches

`git checkout <branch-name>`


## Merging

### Merge changes from branchA into branchB

`git checkout branchB`
`git merge branchA`

if there are no conflicts then it create a merge commit.


### Conflict:  When two branches contains different changes in the same file it raise a conflict and it must be resolved  manually.


