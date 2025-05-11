## Shiraztux Git Tutorial 

https://www.w3schools.com/git

Cheat Sheet we used:
```
## git version and help
# Check if Git is installed on your system and what its version is
git --version
# Git help and available arguments
git --help
# Get help for a specific command
git <command> --help

## Setup & Configuration
# Initialize a new repository
git init
# Configure your username and email
git config --local user.name "Your Name"
git config --local user.email "me@my-email.com"

## Add changes to staging area
# Stage a specific file
git add <file>
# Stage multiple files
git add <file1> <file2> <file3>
# Stage a file in a directory
git add <dir>/<file>
# Stage all changes (new, modified, deleted)
git add .

## Check status of your repo
git status

## Commit staged changes:
git commit -m "Your desired commit message"

## Display a list of all local branches in the repository along with the latest commit on each branch
git branch -v

## Viewing History
# Show commit history
git log
# Show a simplified commit history (in one line)
git log --oneline


## Show differences
# Differences between the staged changes and the last commit
git diff --staged
Differences between the HEAD and a specific commit
git diff HEAD <commit-id>

## Unstaging
# Unstages entire changes in staging area
git reset
# Unstage a single file
git restore --staged file.txt

## Check-out
# Check out a specific commit
git checkout <commit-it>
# Check out to the latest commit on master branch
git checkout master

## Remote repositories
# Add a remote repository
git remote add origin https://codeberg.org/username/repo-name.git
# View remote repositories
git remote -v
# Push the changes from the master branch to a remote repository
git push -u origin master

```


