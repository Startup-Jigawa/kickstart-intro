# Git and GitHub Setup Guide

## Installing Git

1. Windows: Download from https://git-scm.com/download/windows
2. Mac: Install using Homebrew with `brew install git`
3. Linux: Use `sudo apt-get install git` (Ubuntu/Debian)

## Setting up GitHub Account

1. Go to https://github.com
2. Click "Sign Up"
3. Follow registration process
4. Verify your email address

## Initial Git Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Setting up SSH Keys (Recommended)

1. Generate SSH key: `ssh-keygen -t ed25519 -C "your.email@example.com"`
2. Add key to GitHub account under Settings > SSH Keys
