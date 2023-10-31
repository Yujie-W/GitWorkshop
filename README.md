# Git

swcarpentry.github.io/git-novice

## Git Config
git config --global user.name "First Last"
git config --global user.email "user.email.com"
git config --global core.editor "nano -w"
git config --list

## Initialization
git init
git checkout -b main
git branch
git status

## Commit
git add README.md
git add .
git add --all
git commit -m "Some commit messages"

## Logs
git log
git diff
git diff --staged
