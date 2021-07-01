# 2021-07-01 GIT BASICS CLASS


- `git init`: initialize git repository in current working directory
- `git status`: gives you the status
- `git add <FILE>`: adds <FILE > to the staging
- `git commit`: creates a commit, you provide message
- `git log`: shows you the log of your commits
- `git log --oneline`: shows you the one line version of log
- `HEAD`: where you currently are (version on your computer)
- `git diff HEAD~<NUM> <FILE>`: compares current file to file <NUM> ago
- `git diff <HASH> <FILE>: compares current file to <HASH> from oneline 

- Use `git status`: to help you find the commands to unstatge or restore file
- `git checkout <HASH> <FILE>`: restore <FILE> to version in <HASH
- git ignores  empty folders
- use `.gitkeep` to keep an empty folder
- use `.gitignore` to ignore files/patterns    

#remotes
-  `ssh-keygen`
-  `git remote add <URL>`: adds the url
- `git push origin main`: push to the main branch to the origin remote
- `git pull origin main`: pull origin to main branch
