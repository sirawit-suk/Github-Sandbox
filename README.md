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

