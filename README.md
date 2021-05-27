# GIT COMMANDS

##Maintainer
```bash
Jiffin Joachim Gomez
jiffin.gomez@reflectionsinfos.com
```

### Global Configuration

Setting Username:

```bash
git config --global user.name "Your name"
```

Setting email-id:

```bash
git config --global user.email "Your email id"
```

Color highlighting
```bash
git config --global color.ui true
git config --global color.status auto
git config --global color.branch auto
```

To view global configurations:
```bash
git config --global --list
```

To view all configuration:
```bash
git config --list
```
### Clone
To clone, copy the url from git repository and go to the folder where you want to clone.

```bash
git clone {url}
```

### Branch
To view current branch
```bash
git branch
```
To create a new branch
```bash
git checkout -b new-branch-name
```
To delete a branch
```bash
git branch -D branchname
```
To rename a branch
git branch -m current-branch-name new-branch-name
### Add files

To add/stage all un added/staged files. PS: Below command will add all changed/new files.

```bash
git add .
```

To add a file to stage:
```bash
git add filename
```

### Status

To view the status of files:
```bash
git status -s
```

### Commit files

To commit the added files with a message:

```bash
git commit -m "Your commit message"
```

### Merge

This command is used to update your local changes with any branches.
Usually before pushing any changes to the remote repository, we update our local repository with the latest files,
From the base branch we are working on.
```bash
git merge origin/features
or
git pull origin/features
```

### Push
This commands pushes your changes to remote repository
```bash
git push
```

### Pull
This command pulls the latest code from the branch
```bash
git pull origin/branchname
```
### Move & Rename
To move or rename
```bash
git mv filename newfilename
```
### Checkout
This is used to switch from one branch to another
```bash
git checkout branchname
```
To create a branch from remote and switch to it.
```bash
git checkout --track origin/branchname
```
### History
To view the history
```bash
git log
```

### Stash

To stash some files, if don't want to commit it.
```bash
git stash
git stash list
git stash pop
```

### Remove a committed file
```bash
git rm file name
```

### Fetch
To fetch all remote branches
```bash
git fetch --all
```


