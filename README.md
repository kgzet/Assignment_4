# Assignment_4
### Personal data:
Kinga Zajdel
### Exercises:
4; 20th March 2024
### Course:
Advanced Toolkit for Bioinformatics Research
### AI usage:
none

---------------------------------------------------------------------------------

##  The most important things and commands I learned about Git
### Commands:
* git clone + link = create local directory and copy the linked repository with remote-tracking branches; it is obligaatory to do this for the first time to copy the remote repository - next time git pull will be needed
* git pull 'remote_name' 'branch_name' = git fetch (fetches the recent commits in the local repository) + git merge (merges the branch from a remote to a local branch) where 'remote_name' is name of the repository and 'branch_name' is the name of the specific branch in that repositiry
* fetch and download content from a remote repository and immediately update the local repository to match that content
* git add "file.py" = add file to staging area, next step is commit (file is still only in our local repository)
* git add . = all files in local directory moved to staging area
* git add -u = as above but only changed files
* git commit -m "description" = all files moved from staging area to localrepo
* git commit -a = git add and git commit
* git push origin main = send files from localrepo to the remote repo (branch main)
* git checkout = change the branch
* git checkout no_of_commit = load repository status as it was right after given commit
* git checkout main + git merge newbranch = add changes done in the newbranch to the main branch
* git diff main..bewbranch = comparison of two given branches (checking if files differ somehow)
* git rm -r = remove directory with all files inside (repository's history will still contain information about removed files)
* 
