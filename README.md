# Git Tutorial
Learning content of git


| Command | Description |
|---------|-------------|
| touch < file > | a new file created |
| mkdir < folder > | a new folder created | 
| rm -rf < file > | file deleted | 
| git init | initialize a repo | 
| git add . | adding all the file in staging area | 
| git status | checking repo status for change |  
| git log | commits history | 
| cat < file > | fetching content form file (for git bash shell) | 
| type < file > | fetching content form file (for cmd/powershell) | 
| git restore --staged < file > | back to unstaged form staged | 
| git reset < commit hash > | delete previous commit | 
| git stashs | sending backstage the changes | 
| git stash pop | again fetching the stash data | 
| git remote -v | for checking link | 
| git remote add origin/upstream < link repo > | for adding link | 
| git remote set-url origin/upstrem < link repo > | for modify link | 
| origin | personal repo | 
| upstream | Public repo where to contribute |
| git push origin branch-name -f | for force push after resetting the git commits | 
| | |
| git config --list | all the details for git configuration file |
| git config --global/local/system user.name | show the name |
| git config --global/local/system user.email | show the email |
| git config --global/local/system user.name "Your name" | setting the name |
| git config --global/local/system user.email "Your email address" | setting the email address |
| | |
| After Merging | |
| git pull upstream main| sync local folder with upstream| 
| git push origin main| sync forked online repo with local origin| 

