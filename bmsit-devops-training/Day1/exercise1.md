# Exercise 1: Git Basics

## Objective
Set up a local Git repository, make your first commit, and push to GitHub.

## What You Will Practice
- Initializing a repository
- Configuring Git identity
- Creating and committing a file
- Connecting and pushing to a remote repository

## Steps
1. Create a new project folder and initialize Git.
2. Configure your Git username and email.
3. Create a sample file and commit it.
4. Add GitHub as remote and push to `main`.

## Commands (Copy/Paste)
```bash
mkdir git-exercise
cd git-exercise
git init

git config --global user.name "Your Name"
git config --global user.email "your@email.com"

echo "Hello DevOps" > app.txt
git add .
git commit -m "Initial commit"

git remote add origin <repo-url>
git branch -M main
git push -u origin main
```

## Notes
- Replace `<repo-url>` with your GitHub repository URL.
- Use `git status` anytime to check your current state.
