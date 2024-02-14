
# Git important Commands


**git Init**  : initializes git repository 

**rm -rf .git/**  : undo git init using force delete

**git config —global user.name**  : adds username

**git config —global user.email**  : adds email

**git config —list or git config -l**   : show the git config list

**git status** : shows the status

**git status -s** : short status or summarize status in short 

**git add <filename>**: adds the file to the staging area

**git commit** : add to repo or unmodified area

**git commit -m “ “**  : commits the change

**git commit -a -m “ “** :skips staging , directly commits

**git ls-files** : shows the list of files 

**git log** : gives the logs

**git log -p -<no. of last commits>** : gives the last number of commits

**git add file** : add certain file

**git add .** : add at once

**git add -A**  : add at once

**touch <filename>**  : creates the file

**vi <filename>**  : helps to write the file content

**cat <filename>** : helps to view the file content

**git diff** : compares from working to last commit

**git diff —staged** : compares staging to last commit

**git rm <file>** : removes from working, staging  as well as from repository

**git rm —cached <file>** : removes from only staging area

**git rm -f** : removes from every where i.e force removal of files

**git rm -r <directory>** : removes or delete the entire directory

**git mv old-file new-file** :rename files in git

**git restore <file>**  : to discard the changes in working 
directory

**git restore —staged <filename>**: restores the file from staging area back to working

**git tag** :show tag lists

**git tag <tag-name>** : creates tag 

**git tag —list** : show the tag lists

git tag  -l  “v1*”: list of version with v1

**git tag show <tag-name>** : show the tag complete details

**git tag -a <tag-name> -m “comments”** : creates tag with message

**git tag —delete <tag-name>**  : deletes the tag

**git checkout <filename>** : matches the change in working to last commit and restores the modified file

**git checkout -f** : This is for all the files changed in working and restores to last commit

**git branch** : show the list of branches

**git branch <branch-name>** : create the branch

**git branch -m <branch-name>**:renames the branch. :not sure

**git checkout <branch-name>**: take you to branch

**git merge <branch-name>** : merge the branch

**git checkout -b <branch-name>** : will create and take directly to the branch

**git branch -d branch_name** :deletes the branch

**git switch -c  <branch-name>** : will create and take directly to the branch ,same as above

**git remote** :display the remote repo

**git remote -v** : show the link path to remote repo

**git remote add origin https::github.com/prashantkrt/My-Learning2.git** : add remote repo with name origin

**git clone  <copy url from GitHub>** :set path where you want to clone and then clone it there

**git push origin master** :  **git push 'remote_name' 'branch_name'** push the master branch to the remote repo origin master and if master not there then it will create new master and then push it. It will first check if master branch is there or not  & if not there then it will create master and point it to local master

**git push -u origin master** : this will create upstream , it links local master branch to matching remote master branch 

**git push —set-upstream origin master** :same as above

**git push** :short-end after fixing upstream

**git push -u origin master** : head : this will now change the remote branch, now sets main in remote and local master

**git pull origin master**

**git branch -u origin/<branch_name>** :this need to be set before
git pull 

**git fetch** : This command will download the changes from a remote repo but will not perform a merge on your local branch 

**git merge** : merges two branch files

**git pull** :fetch and merge

**Git push —delete origin <branch-name>** : delete the branch name in remote

