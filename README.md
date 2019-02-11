Git Commands
============

_A list of my commonly used Git commands_

### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git config --global user.name "[Username]"` | Git global setup |
| `git config --global user.email "[User Email]"` | Git global setup |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |
| `git init` | Initialize a local Git repository for existing project |
| `git remote add origin [Project URL]` | Initialize a local Git repository (also run command for add, commit, push) |

### Basic Git Command

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git log` | View changes |
| `git branch` | List branches |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branchName]` | Delete a remote branch |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add .` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git pull --rebase=preserve --allow-unrelated-histories` | Pull from origin allow unrelatedhistories |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -b [remote branch name] origin/[remote branch name]` | Checkout from remote |
| `git checkout -b [branch name]` | Create a new branch and switch to it |

### Important Git Command

| Command | Description |
| ------- | ----------- |
| `git merge --abort` | Discard merge conflict |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git remote prune origin --summary` | update local branch from origin |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |
| `git diff [source branch] [target branch}` | Preview changes before merging |


