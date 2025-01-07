# Task 3: Collaboration and Advanced Features

## Objectives
- Learn branching and merging
- Understand pull requests
- Collaborate with others
- Handle merge conflicts

## Steps

1. **Working with Branches**
   ```bash
   # Create and switch to new branch
   git checkout -b feature-branch

   # List all branches
   git branch

   # Switch between branches
   git checkout main
   ```

2. **Pull Requests**
   - Make changes in feature branch
   - Push to GitHub
   - Create Pull Request
   - Review and merge changes

3. **Collaboration Workflow**
   ```bash
   # Update your repository
   git pull origin main

   # Create feature branch
   git checkout -b new-feature

   # Push branch to remote
   git push -u origin new-feature
   ```

4. **Handling Merge Conflicts**
   - Identify conflict markers
   - Choose changes to keep
   - Commit resolved conflicts

## Advanced Topics
- Git rebase vs merge
- Cherry-picking commits
- Git hooks
- GitHub Actions basics

## Best Practices
- Write clear commit messages
- Review changes before committing
- Keep branches updated
- Document your code

## Troubleshooting
- Merge conflicts: Use visual tools
- Branch issues: Check branch status
- Remote problems: Verify remote URLs

## Additional Resources
- [Advanced Git Tutorial](https://www.atlassian.com/git/tutorials/advanced-overview)
- [GitHub Actions](https://docs.github.com/en/actions)
- [Git Branching Strategies](https://nvie.com/posts/a-successful-git-branching-model/)
