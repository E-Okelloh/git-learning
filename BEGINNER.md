# Git Beginner's Guide

## Basic Configuration

```bash
# Set your username (global for all projects)
git config --global user.name "Your Name"

# Set your email (global for all projects)
git config --global user.email "your.email@example.com"

# Set your default editor (VSCode in this example)
git config --global core.editor "code --wait"

# Initialize a new Git repository in current directory
git init

# Clone an existing repository
git clone https://github.com/user/repo.git

# Clone a specific branch
git clone -b branch-name https://github.com/user/repo.git

# Check status of working directory
git status

# Stage all changes
git add .

# Stage specific file
git add filename.ext

# Commit changes with message
git commit -m "Descriptive commit message"

# View commit history
git log

# View compact commit history
git log --oneline --graph --all


#Undoing Changes
# Unstage a file (keep changes)
git restore --staged filename.ext

# Discard changes in working directory
git restore filename.ext

# Amend the last commit (change message or add files)
git commit --amend
