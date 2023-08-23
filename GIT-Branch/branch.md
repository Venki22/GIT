### Checkout Commit
git checkout commit-id
git switch -

### Switch to master
git checkout master

### Creating new branch List all branches used in current working git repository
git branch
git branch –list

### Create branch using below command
git branch  new-branch-name    
git checkout new-branch-name
git checkout feature
git checkout -b new-branch-name
git checkout - 

### In order to create branch in remote GitHub use below command
git push origin new-branch-name
git push origin Stage

### Deleting branch locally
git branch -d branch-name 
git branch -D branch-name

### Deleting a branch remotely
git push origin –-delete new-branch-name
git push origin –-delete feature

### Shotcut command for deleting
git push origin: new-branch-name
git push origin: feature

### Get all change history of origin
git fetch origin

### Update the current branch from its origin using a single command
git pull origin

### List all local and remote branches of the current git.
git branch -a

### List only remote branches of the current Git.
git branch -r

### Rename branch in local
git branch -m old-branch-name new-branch-name

### How can I know if a branch has been already merged into master
git branch –merged
**lists branches merged in HEAD**

### List local branches
git branch   		                

### List local branches verbose
git branch -v 

### List remote and local branches		        
git branch -a 
git branch -all 

### List remote and local branches		         
git branch -av

### List remote branches		       
git branch -r		                
git branch -rv

### List remote branches with latest commit		        
git branch --contains commit-id 

### List branches merged into master
git branch --merged master

### List branches that have not been merged 
git branch --no-merged  

