# Exercise: Resolving Merge Conflicts

## Objective
Learn how to identify and resolve Git merge conflicts.

## Setup

1. Create a conflict scenario:
```bash
# Create two branches
git checkout -b feature1
git checkout -b feature2

# Make conflicting changes in each branch
```

## Resolution Steps

1. Attempt to merge:
```bash
git checkout main
git merge feature1
git merge feature2  # This will cause conflict
```

2. Resolve conflicts in your editor

3. Complete the merge:
```bash
git add .
git commit -m "Resolve merge conflicts"
```

## Verification
- [ ] Conflict created and identified
- [ ] Conflicts resolved successfully
- [ ] Final merge completed

## Tips
- Always pull latest changes before starting work
- Communicate with team members about overlapping work
- Use git status to check conflict status
