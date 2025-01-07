# Frequently Asked Questions

## General Questions

### What is Git?
Git is a distributed version control system that helps track changes in source code during software development.

### What is GitHub?
GitHub is a web-based hosting service for Git repositories that adds collaboration features like bug tracking, feature requests, and task management.

### How do I create a repository?
1. Click the '+' icon in the top-right corner
2. Select "New repository"
3. Fill in the repository details
4. Click "Create repository"

### What's the difference between Git and GitHub?
Git is the version control system itself, while GitHub is a platform that hosts Git repositories and adds collaborative features.

## Common Issues

### How do I resolve merge conflicts?
Merge conflicts occur when competing changes are made to the same line of a file. To resolve:
1. Open the conflicted file
2. Look for conflict markers (<<<<<<, =======, >>>>>>>)
3. Choose which changes to keep
4. Remove the conflict markers
5. Save the file and commit

### How do I undo my last commit?
To undo your last commit while keeping the changes staged:
```bash
git reset --soft HEAD~1
```

To completely remove the last commit and its changes:
```bash
git reset --hard HEAD~1
```

### Why can't I push to a repository?
Common reasons include:
1. Lacking necessary permissions
2. Repository is outdated (needs to pull first)
3. Unresolved merge conflicts
4. Protected branch restrictions

### How do I update my fork with changes from the original repository?
1. Add the original repository as upstream:
```bash
git remote add upstream original-repo-url
```
2. Fetch and merge changes:
```bash
git fetch upstream
git merge upstream/main
```
## Repository Management

### How do I delete a repository?
1. Go to repository settings
2. Scroll to bottom "Danger Zone"
3. Click "Delete this repository"
4. Type repository name to confirm

### How do I rename a repository?
1. Go to repository settings
2. Under "Repository name", enter new name
3. Click "Rename"

### How do I transfer a repository?
1. Go to repository settings
2. Under "Transfer ownership"
3. Choose new owner
4. Confirm transfer details
### How do I change repository visibility?
1. Go to repository settings
2. Under "Danger Zone"
3. Click "Change visibility"
4. Select public, private, or internal
5. Confirm the change

### How do I add collaborators?
1. Go to repository settings
2. Click "Collaborators"
3. Click "Add people"
4. Enter username, full name, or email
5. Select access level
6. Click "Add"

### How do I protect branches?
1. Go to repository settings
2. Click "Branches"
3. Under "Branch protection rules"
4. Click "Add rule"
5. Configure protection settings
6. Click "Create"
## Git Commands

### What are the basic Git commands?
Common Git commands include:
- `git init`: Initialize a new repository
- `git clone`: Copy a repository
- `git add`: Stage changes
- `git commit`: Save changes
- `git push`: Upload changes
- `git pull`: Download changes
- `git status`: Check repository status
- `git branch`: Manage branches

### How do I create and switch branches?
To create a new branch:
```bash
git branch branch-name
```

To switch to a branch:
```bash
git checkout branch-name
```

Or do both at once:
```bash
git checkout -b branch-name
```