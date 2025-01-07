# Exercise: Creating Your First Repository

## Creating a Repository on GitHub

1. Log into GitHub
2. Click the '+' icon in the top right
3. Select "New repository"
4. Fill in:
   - Repository name
   - Description (optional)
   - Public/Private setting
   - Initialize with README option
5. Click "Create repository"

## Initialize Local Repository

```bash
mkdir my-first-repo
cd my-first-repo
git init
git add README.md
git commit -m "Initial commit"
git branch -M main
git remote add origin <repository-url>
git push -u origin main
```

## Practice Tasks

1. Create a new repository on GitHub
2. Initialize it locally
3. Add a simple README.md
4. Push your changes
