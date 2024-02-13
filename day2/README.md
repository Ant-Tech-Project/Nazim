# Git Branching and Merging

Welcome to Day 2 of our Git tutorial series! Today, we'll dive into the concepts of remote repositories, branching, merging, and essential commands like `git clone`, `git push`, and `git pull`.

## 1) Remote Repositories

Remote repositories are copies of your project stored on servers, typically hosted by platforms like GitHub, GitLab, or Bitbucket. These repositories allow collaboration between multiple developers by providing a centralized location to share code.

## 2) Git Commands for Remote Repositories

- `git clone`: Copies a remote repository to your local machine.
  ```bash
  git clone <remote_repository_url>
- `git push`: Uploads local changes to the remote repository.
  ```bash
  git push origin <branch_name>
- `git pull`: Fetches changes from the remote repository and merges them into your local branch.
  ```bash
  git pull origin <branch_name>

## 2) Branches and Their Importance
Branches in Git are independent lines of development that allow you to work on features or fixes without affecting the main codebase. They provide isolation for experimental changes and enable parallel development.
## 4) Branch Management

- `git branch` <branch_name>: Creates a new branch.
  ```bash
  git branch feature-xyz
- `git checkout` <branch_name>: Switches to the specified branch.
  ```bash
  git checkout feature-xyz
- `git checkout` feature-xyz
  ```bash
  git branch -d feature-xyz
## 5) Merging Process in Git
Merging combines changes from different branches into one branch, typically the main branch (e.g., master).
- `git merge` <branch_name>: Merges changes from the specified branch into the current branch.
  ```bash
  git merge feature-xyz
### Example Scenario:
Clone a remote repository

```bash
git clone <remote_repository_url>
```
Create a new branch for a feature:
```bash
git branch feature-xyz
git checkout feature-xyz
```
Make changes, commit them, and push the branch to the remote repository:
```bash
git add .
git commit -m "Implemented feature XYZ"
git push origin feature-xyz
```
Switch back to the main branch (e.g., master) and merge the feature branch:
```bash
git checkout master
git merge feature-xyz
```
Push the changes to the remote repository:
```bash
git push origin master
```
> *@NaziMv*