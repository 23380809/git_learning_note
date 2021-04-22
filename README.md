# git learning notes

### ls -la  
show all the file in the directory

### touch README.md    
adding new file

### git add .    
add all the files to the staged area

### git add file_name    
add certain file to the staged area

### git status
check out all the files that's ready to be committed

### git commit -m"message"  
commit file to the local repository

### git remote add origin ssh-directory    
adding origin

### git push -u origin master
setting origin and master so next time you won't have to type out everything again

### git branch
checking which branch you're in and what branches you have currently

### git branch -d branch_name
deleting branch

### git push -u origin branch_name
push the feature branch to github

### git checkout -b branch_name
creating a new branch

### git diff another_branch 
comparing the differences between two branches

### git commit -am "message"
commit without adding files to staged repository

### git merge master
merging with master

### git pull origin master
pull down files from github

### git reset file_name
unstaged files

### git reset HEAD~1
uncommit files. 

### git log
you can see all the commits with commit message with it's hash code

### git reset hash_code
unstage changes after reset

### git reset --hard hash_code
completely remove changes
