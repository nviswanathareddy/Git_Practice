# Git_Practice
### Test Repository to Test Git Practices


### Git Basic
```bash
# checks the current status of the git repository
git status
```
### Git Init
```bash
# Initializes empty git repository to in the current folder
git init
```
### Git Clone
```bash
# clones the remote repository to local
git clone git@github.com:nviswanathareddy/Git_Practice.git
```
### Git Configure username and email
```bash
# lists the cofiguaration file
git config --list
# configuring username
git config --global user.name "nviswanathareddy"
# shows the  username
git config user.name
# shows the email
git config user.email
# configuring email
git config --global user.email "viswanathareddynagireddy@gmail.com"
```
### Git Diff
```bash
# shows all the edited files in working area
git diff
# shows edited content of single file
git diff index.html
# shows edited content in staging area
git diff --staged test.html
```
### Git Remote
```bash
# adding the remote repository to local repository
git remote add origin git@github.com:nviswanathareddy/Git_Practice.git
# shows short name of remote repository
git remote
# shows full url
git remote -v
```
### Git Log
```bash
# shows log history
git log
# shows log history in oneline
git log --oneline
# shows the log related to the specific author
git log --author "nviswanathareddy"
```

### Git Add
```bash
# adds the single file to staging area
git add index.html
# adds all the files to staging area
git add .
# removes the files from staging area to working area
git restore --staged test.html
```
### Git Commit
```bash
# commits the code from staging area to local repository
git commit - m "added index.html file"
```
### Git Push
```bash
# pushes the code from local repository to remote repository
git push origin main
```
# Git Branches