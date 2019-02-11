Git Commands
============

_A list of my commonly used Git commands_

### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Git Command

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git log` | View changes |
| `git branch` | List branches |
| `git branch -a` | List all branches (local and remote) |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add .` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branchName]` | Delete a remote branch |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |

### Important Git Command

| Command | Description |
| ------- | ----------- |
| `git merge --abort` | Discard merge conflict |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |
| `git diff [source branch] [target branch}` | Preview changes before merging |

### Special Command

| Command | Description |
| ------- | ----------- |
| `git pull --rebase=preserve --allow-unrelated-histories` | Pull from origin allow unrelatedhistories |
| `git remote prune origin --summary` | update local branch from origin |
