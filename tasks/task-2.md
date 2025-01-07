# Task 2: Basic Git Operations

## Objectives
- Create your first repository
- Learn basic Git commands
- Understand the Git workflow
- Make your first commit

## Steps

1. **Create a New Repository**
   ```bash
   # Create and navigate to a new directory
   mkdir my-first-repo
   cd my-first-repo

   # Initialize Git repository
   git init
   ```

2. **Basic Git Workflow**
   ```bash
   # Check repository status
   git status

   # Create a sample file
   echo "# My First Repository" > README.md

   # Stage changes
   git add README.md

   # Commit changes
   git commit -m "Initial commit: Add README"
   ```

3. **Connect to GitHub**
   - Create new repository on GitHub
   - Link local repository:
   ```bash
   git remote add origin https://github.com/username/repo-name.git
   git branch -M main
   git push -u origin main
   ```

## Practice Exercises
1. Create a new file and commit it
2. Modify existing file and commit changes
3. Check commit history using `git log`

## Common Commands
```bash
# View status
git status

# Stage files
git add <filename>
git add .  # Stage all changes

# Commit changes
git commit -m "message"

# View history
git log

# Check remote connections
git remote -v

# Push changes
git push origin main
```