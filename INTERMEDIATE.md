
## 3. Sample Content for INTERMEDIATE.md

```markdown
# Intermediate Git Concepts

## Branching Workflow

```bash
# Create a new branch
git branch new-feature

# Switch to a branch
git checkout new-feature

# Create and switch to a new branch (shortcut)
git checkout -b new-feature

# List all branches
git branch -a

# Delete a branch (safe, checks merge status)
git branch -d old-branch

# Force delete a branch
git branch -D old-branch


#MERGING

# Merge another branch into current branch
git merge feature-branch

# Abort a merge in progress
git merge --abort

# Create a merge commit even if fast-forward is possible
git merge --no-ff feature-branch

#Remote Operations
# Add a remote repository
git remote add upstream https://github.com/user/repo.git

# List remotes
git remote -v

# Fetch changes from remote
git fetch upstream

# Push branch to remote
git push -u origin branch-name

# Delete remote branch
git push origin --delete old-branch
