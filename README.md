# Git and GitHub Beginners Guide

## 1. Introduction

Git is a version control system that tracks changes made to files. It helps developers save different versions of their work and return to earlier versions when needed.

GitHub is an online platform that hosts Git repositories. It allows developers to share code, review changes, manage tasks, and collaborate on projects.

## 2. Why Use Git and GitHub?

Git and GitHub help developers:

- Track changes to project files.
- Maintain a history of their work.
- Create separate branches for new features.
- Review changes before merging them.
- Collaborate on software projects.
- Recover earlier versions of files.

## 3. Installing and Configuring Git

Download Git from https://git-scm.com/downloads and install it on your computer.

Open PowerShell and verify the installation:

```bash
git --version
```

Configure your name and email address:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Replace the example values with your own information.

## 4. Basic Git Commands

Check the current status of your files:

```bash
git status
```

Stage a file for committing:

```bash
git add README.md
```

Save staged changes:

```bash
git commit -m "docs: update README"
```

Upload commits to GitHub:

```bash
git push
```

Download and integrate changes from the remote repository:

```bash
git pull
```

## 5. Creating and Cloning Repositories

Create a local Git repository:

```bash
git init
```

Copy an existing remote repository to your computer:

```bash
git clone REPOSITORY_URL
```

Replace `REPOSITORY_URL` with the actual repository URL.

## 6. Conclusion

Git tracks file changes, while GitHub makes it easier to store repositories online and collaborate with other developers. Learning basic Git commands is the first step toward managing projects effectively.
