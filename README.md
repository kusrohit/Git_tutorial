# Git Tutorial
Learning content of git


| Command | Description |
|---------|-------------|
| touch <file> | a new file created |
| mkdir <folder> | a new folder created | 
| rm -rf <file> | file deleted | 
| git init | initialize a repo | 
| git add . | adding all the file in staging area | 
| git status | checking repo status for change |  
| git log | commits history | 
| cat <file> | fetching content form file | 
| git restore --staged <file> | back to unstaged form staged | 
| git reset <commit hash> | delete previous commit | 
| git stashs | sending backstage the changes | 
| git stash pop | again fetching the stash data | 
| git remote -v | for checking link | 
| git remote add origin/upstream <link repo> | for adding link | 
| git remote set-url origin/upstrem <link repo> | for modify link | 
| origin | personal repo | 
| upstream | Public repo where to contribute |
| git push origin branch-name -f | for force push after resetting the git commits | 

| After Merging ||
|-------------|-------------------------------| 
| git pull upstream main| sync local folder with upstream| 
| git push origin main| sync forked online repo with local origin| 

