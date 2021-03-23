## create a new repository
echo "# Github-Sandbox" >> README.md

- git init
- git add README.md
- git commit -m "first commit"
- git branch -m main
- git remote add origin git@github.com:sirawit-suk/Github-Sandbox.git
- git push -u origin main

## …or push an existing repository
- git remote add origin git@github.com:sirawit-suk/Github-Sandbox.git
- git branch -M main
- git push -u origin main

## keep tracking
- git status
- git config --global --list
- git config --list
- git branch
- git remote 
- git remote -v
- git branch --remote

## normal work flow
- git add .
- git commit -m "test"
- git push -u origin main // git push upstream < remote-alias > < branch-name >


newnewnew
## advance work flow colaboration
- git checkout -b < new-branch-name > // for created new branch and switch
- git checkout < branch-name >
- git branch < new-branch-name>

#### and before merge don't forget to fetch and pull data (update to local)
#### before merge... stand in that branch and merge another branch in ... like (standing on develop branch now <--- feature branch) 
- git merge --no-ff < small branch > // for keep history of that branch

- git branch -d < branch-name-to-delete >

xx
asdasdas
adsdasd
asdasdad
asdasdad