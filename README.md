# Git

[Tutorial](swcarpentry.github.io/git-novice)


## Git Config
```
git config --global user.name "First Last"
git config --global user.email "user.email.com"
git config --global core.editor "nano -w"
git config --list
```


## Initialization
```
git init
git checkout -b main
git branch
git status
git status --ignored
```


## Commit
```
git add README.md
git add .
git add --all
git commit -m "Some commit messages"
```


## Logs
```
git log
git diff
git diff --staged
git diff HEAD~1 README.md
git diff HEAD~1
git diff HEAD~3
git diff 46ee645737acbca62e3b3b2231e0af5016285e03 README.md
```


## Pull out History
```
git checkout 46ee645737acbca62e3b3b2231e0af5016285e03 README.md
git checkout 46ee645737acbca62e3b3b2231e0af5016285e03
git checkout main
```


## Ignore
```
mkdir data
touch a.csv b.csv data/d.csv data/e.out
nano .gitignore
```


## Connect to Github
```
git remote add origin https://github.com/Yujie-W/GitWorkshop.git
git remote -vl
ssh-keygen -t ed25519 -C "Yujie-W@GitHub"
ssh -T git@github.com
```


## Push and Pull
```
git push
git pull
```
