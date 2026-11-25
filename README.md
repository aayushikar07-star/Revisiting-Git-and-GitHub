# Git & GitHub – Revision Notes

A beginner-friendly repository to revisit, understand and practise Git and GitHub concepts, commands and workflows.

## 🎯 Objective

- Revise the fundamentals of Git and GitHub.
- Understand version control and how it works.
- Practise commonly used Git commands.
- Learn how to manage repositories and branches.
- Understand how to contribute to open-source projects.
- Become comfortable with GitHub collaboration workflows.

## 📌 1. Introduction

### What is Git?
Git is a distributed version control system used to track changes in source code and manage different versions of a project.

### What is GitHub?
GitHub is a cloud-based platform that hosts Git repositories and allows developers to collaborate on projects.

### Git vs GitHub

| Git | GitHub |
|---|---|
| Version control system | Code hosting platform |
| Works locally | Works online |
| Tracks changes | Hosts repositories |
| Manages branches | Supports collaboration and pull requests |

## 📌 2. Git Installation and Configuration

Check Git version:

```bash
git --version
```

Configure username:

```bash
git config --global user.name "Your Name"
```

Configure email:

```bash
git config --global user.email "your-email@example.com"
```

Check configuration:

```bash
git config --list
```

## 📌 3. Basic Git Commands

| Command | Purpose |
|---|---|
| `git init` | Initialize a Git repository |
| `git status` | Check repository status |
| `git add .` | Stage all changes |
| `git add filename` | Stage a specific file |
| `git commit -m "message"` | Save changes |
| `git log` | View commit history |
| `git diff` | View unstaged changes |
| `git clone URL` | Clone a repository |
| `git pull` | Fetch and integrate remote changes |
| `git push` | Upload local commits |

## 📌 4. Git Workflow

The basic Git workflow:

1. Create or modify files.
2. Check changes using `git status`.
3. Stage changes using `git add`.
4. Commit changes using `git commit`.
5. Push changes using `git push`.

```bash
git status
git add .
git commit -m "Initial commit"
git push
```

## 📌 5. Branching and Merging

Branches allow developers to work on different features without affecting the main branch.

```bash
git branch
git branch feature-name
git switch feature-name
git switch -c new-branch
git merge feature-name
git branch -d feature-name
```

## 📌 6. Working with Remote Repositories

Connect a local repository to GitHub:

```bash
git remote
