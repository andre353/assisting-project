# Git Project №1

---

The **Project** has been created as a part of homework to prove:

* the knowledge of Git
* the knowledge of GitHub
* the knowledge of Markdown

---

## Project Initiation

### 1. Create a local project folder
mkdir my-project
cd my-project

### 2. Initialize a Git repository
git init

### 3. Check repository status
git status

### 4. Add files to the index
git add .

### 5. Make the first commit
git commit -m "Initial commit"

--- 

## Commits 

### Add changes to the index
git add .

### Commit the changes with a message
git commit -m "Add initial structure to the project"

### View commit history
git log

### Change the last commit message (if it hasn't been pushed yet)
git commit --amend -m "Обновлённый комментарий к коммиту"

### Revert changes in a file before committing
git checkout -- filename

### Remove a file from the index but keep it in the working directory
git reset filename

---

## Local and remote repoes connection

### Connect a remote repository
git remote add origin https://github.com/<username>/<repository>.git

### Verify the connection
git remote -v

### Push changes to GitHub
git push -u origin main  # или master

---

## Typical commands for everyday work

### Create a new branch and switch to it
git checkout -b feature/new-function

### Switch to another branch
git checkout main

### Update your local copy from GitHub
git pull origin main

### Merge changes between branches
git merge feature/new-function
