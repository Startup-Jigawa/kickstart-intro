# Branching and Merging in Git

## Understanding Branches

A branch in Git is a lightweight movable pointer to a commit. It allows you to:
- Develop features isolated from each other
- Work on multiple versions of code simultaneously
- Maintain different environments (development, staging, production)

## Basic Branch Commands

```bash
# Create a new branch
git branch feature-name

# Switch to a branch
git checkout feature-name

# Create and switch in one command
git checkout -b feature-name

# List all branches
git branch -a
```

## Merging Basics

Merging combines changes from different branches:

```bash
# Switch to target branch (usually main)
git checkout main

# Merge feature branch into current branch
git merge feature-name
```

## Best Practices

1. Keep branches focused and short-lived
2. Use descriptive branch names
3. Delete merged branches to maintain cleanliness
4. Regularly sync with the main branch
