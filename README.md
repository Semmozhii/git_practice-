# Git and GitHub Practice

## About This Repository

This repository documents my hands-on learning of Git, GitHub, version control, branching, merging.

## Project Structure

## 1. Git Configuration

Check Git version:

```bash
git --version
```

Configure username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Check configuration:

```bash
git config --global user.name
git config --global user.email
```

## 2. Basic Git Commands

Initialize a repository:

```bash
git init
```

Check repository status:

```bash
git status
```

Add files to staging:

```bash
git add .
git add index.html
```

Commit changes:

```bash
git commit -m "Initial commit"
```

View commit history:

```bash
git log --oneline
```

## 3. GitHub Commands

Connect local repository to GitHub:

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY.git
```

View remote repositories:

```bash
git remote -v
```

Rename branch:

```bash
git branch -M main
```

Push code to GitHub:

```bash
git push -u origin main
```

Pull changes:

```bash
git pull origin main
```

Clone a repository:

```bash
git clone REPOSITORY_URL
```

## 4. Git Branching

View branches:

```bash
git branch
```

Create and switch to a new branch:

```bash
git switch -c feature-profile
```

Switch to main:

```bash
git switch main
```

Push a new branch:

```bash
git push -u origin branch-name 
```

Merge a branch locally:

```bash
git merge branch-name
```

## 5. Pull Request Workflow

1. Create a feature branch.
2. Make code changes.
3. Stage and commit changes.
4. Push the feature branch to GitHub.
5. Create a Pull Request.
6. Review the changes.
7. Merge the Pull Request into main.

