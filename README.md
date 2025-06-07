# Comprehensive GitHub CLI Demo

This repository demonstrates the usage of GitHub Command Line Interface (CLI) tools for common version control operations. Learn how to efficiently manage your GitHub repositories and workflows using command-line commands.

## Overview

This guide will walk you through basic GitHub operations using CLI commands, including:
- Repository creation and cloning
- Committing changes
- Managing branches
- Pull requests
- Issue tracking

Stay tuned for detailed examples and best practices!

## Basic Git Commands

### Repository Setup
```bash
git clone [repository-url] # Clone a repository
git remote add origin [repository-url] # Add remote repository
git init # Initialize a new repository
```

### Version Control
```bash
git --version # Check Git version
git status # Check repository status
git remote -v # List remote repositories
```

### Basic Operations
```bash
git add . # Stage all changes
git commit -m "message" # Commit changes
git pull # Pull changes from remote
git push # Push changes to remote

### Advanced Operations
```bash
git stash # Temporarily save changes
git stash pop # Apply saved changes
git stash list # List saved stashes
git log # View commit history
git log --oneline # Compact commit history
git reset --hard HEAD # Reset to last commit
```

### Branch Management
```bash
git branch # List branches
git checkout -b branch-name # Create and switch branch
git merge branch-name # Merge branches
git branch -d branch-name # Delete branch
```

### Troubleshooting
```bash
git reflog # View reference logs
git revert commit-id # Revert specific commit
git reset --soft HEAD~1 # Undo last commit
git clean -fd # Remove untracked files
``` GitHub CLI Demo

