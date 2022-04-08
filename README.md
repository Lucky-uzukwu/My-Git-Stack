# My-Git-Stack
Repo of all the Git commands i come across as useful. Updated frequently


## Branches

### Search if a commit exists in a branch
git branch --contains $COMMIT_ID
#### Explanation : 
This would list out all the branches that contains that commit. Adding {--a} option would also search through remote branches

### Undo all local changes to a branch
git reset --hard
#### Explanation : 
This would undo all local changes you made to files in a branch

### Force Checkout of a branch
git checkout $BRANCH_NAME --force
#### Explanation : 
This forcefully checks out of a branch

