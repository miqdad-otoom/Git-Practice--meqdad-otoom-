# Git-Practice--meqdad-otoom-
My Homework for My AI Training

## Task Summary
This repository contains solutions for the Git & GitHub assignment, including theoretical answers and practical Git tasks.

## Theoretical Questions & Answers

### 1. What is the difference between Git and GitHub?
- **Git** is a distributed version control system that allows developers to track changes in their code, collaborate with others, and manage different versions of a project locally.
- **GitHub** is a cloud-based platform that hosts Git repositories and provides collaboration tools like Pull Requests, Issues, and project management features. Git is the tool, GitHub is a service that uses Git.

---

### 2. Explain the difference between `git pull` and `git fetch`.
- **`git fetch`** downloads changes from the remote repository to your local repository **but does not merge them** into your current branch. It updates your remote-tracking branches.
- **`git pull`** is a combination of `git fetch` followed by `git merge`. It downloads changes and **automatically merges them into your current local branch**.

---

### 3. What is the purpose of `.gitignore` file?
- The `.gitignore` file tells Git **which files and directories to ignore** (not track or commit) in the version control system.
- It is used to avoid committing unnecessary files like Python cache files (`__pycache__/`, `.pyc`), logs, temporary files, IDE settings, and environment files that are specific to local development setups.

---

### 4. Describe the steps to contribute to an open-source project on GitHub.
1. **Fork** the repository to your own GitHub account.
2. **Clone** the forked repository to your local machine.
3. Create a **new branch** for your changes.
4. Make your changes and **commit** them with clear commit messages.
5. **Push** the branch to your forked repository on GitHub.
6. Open a **Pull Request (PR)** to the original repository.
7. Collaborate with the project maintainers for review and feedback.
8. Once approved, the PR will be **merged** into the original project.

---
