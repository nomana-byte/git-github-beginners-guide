# A Beginner's Guide to Git and GitHub

## Introduction

Git is a version control system that tracks changes to files. GitHub is an online platform that allows people to store projects and collaborate with others.

This guide explains the basic Git commands and how to work collaboratively using GitHub.

## 1. Installing Git

Download Git from https://git-scm.com/downloads.

Check whether Git is installed by running:

```bash
git --version
```

Configure your name and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

## 2. Creating and Cloning a Repository

Create a new local repository:

```bash
git init
```

Download an existing GitHub repository:

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

Replace the example URL with the actual repository URL.

## 3. Staging and Committing Changes

Check the current status:

```bash
git status
```

Stage a file:

```bash
git add README.md
```

Save the staged changes in Git history:

```bash
git commit -m "Add project documentation"
```

## 4. Viewing Git History

Display the commit history:

```bash
git log
```

Display a compact graph of commits and branches:

```bash
git log --oneline --graph --all
```

## 5. Working with Branches

Branches allow team members to work on separate tasks.

Create a new branch:

```bash
git switch -c feature/introduction
```

List branches:

```bash
git branch
```

Switch back to the main branch:

```bash
git switch main
```

## 6. Pushing Changes to GitHub

Upload a branch to GitHub:

```bash
git push -u origin feature/introduction
```

Later, upload additional commits using:

```bash
git push
```

## 7. Pull Requests and Code Reviews

A Pull Request proposes changes from one branch to another.

1. Push the feature branch to GitHub.
2. Open the repository's Pull requests tab.
3. Create a Pull Request targeting main.
4. Link the related Issue.
5. Ask the other team member to review the changes.
6. Address feedback and merge after approval.

## 8. GitHub Issues and Project Boards

Issues are used to organize tasks and improvements.

A Project Board helps track progress using statuses such as To Do, In Progress, and Done.

The team should assign Issues to individual members and update the board as work progresses.

## 9. Resolving Merge Conflicts

A merge conflict can occur when two branches modify the same part of a file.

To resolve it:

1. Read the conflicting sections carefully.
2. Decide which changes should be kept.
3. Edit the file and remove the conflict markers.
4. Stage the resolved file.
5. Commit the resolution.
6. Push the updated branch and complete the Pull Request.

The team will document its actual conflict-resolution process in CONFLICT-RESOLUTION.md.

## 10. Best Practices

- Use descriptive branch names.
- Make small, focused commits.
- Write meaningful commit messages.
- Review changes before merging.
- Connect Pull Requests to Issues.
- Delete feature branches after merging.
- Keep project documentation updated.

## Conclusion

Git and GitHub make it easier to track changes, collaborate on projects, review contributions, and maintain reliable documentation.