# Task 1: Getting Started with GitHub

## Objectives
- Create a GitHub account
- Install Git on your local machine
- Learn basic Git configuration
- Understand Git terminology

## Steps

1. **Create GitHub Account**
   - Go to [GitHub.com](https://github.com)
   - Click "Sign Up"
   - Choose a username, email, and password
   - Verify your email address
   - Enable two-factor authentication (recommended)

2. **Install Git**
   - Download Git from [git-scm.com](https://git-scm.com)
   - Windows: Use the official installer
   - Mac: Use Homebrew: `brew install git`
   - Linux: `sudo apt-get install git` (Ubuntu/Debian)
   - Verify installation: `git --version`

3. **Configure Git**
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   git config --global init.defaultBranch main
   ```

4. **Learn Basic Terms**
   - Repository (repo): Project storage location
   - Commit: Saved changes snapshot
   - Branch: Independent line of development
   - Clone: Copy of a repository
   - Push: Upload changes
   - Pull: Download changes

## Verification
Run these commands to verify your setup:
```bash
git --version
git config --list
```
