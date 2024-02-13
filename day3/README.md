# Git Branching and Merging

Welcome to day 3 of your Git exploration! Today we'll dive into the world of conflicts, those pesky situations where multiple developers make changes to the same files. We'll learn what causes them, how to deal with them, and put our skills to the test with some practical exercises.

## 1. What Can Cause a Conflict?

### *Conflicts arise when two or more developers edit the same lines of code in different branches. This can happen due to:*
- **Concurrent Modifications:** Two developers working on the same file at the same time, unaware of each other's changes.
- **Branch Merging:** When merging branches, Git might detect overlaps, leading to conflict markers.
- **Deleted Files:** One developer deletes a file while another modifies it, creating a conflict upon merging.
## 2. Strategies for Conflict Resolution:

- **Identify the Conflict:** Use `git status` to list conflicting files and `git diff` to visualize the changes.
- **Understand the Changes:** Carefully analyze the conflicting lines, considering the context and intentions behind each modification.
- **Choose the Best Version:** Select the version that aligns best with project requirements and coding standards.
- **Merge Manually:** Edit the conflicting file, removing conflict markers and combining relevant changes.
- **Use Git Commands:** Techniques like git checkout --ours, git checkout --theirs, and git merge can help accept specific versions or merge automatically.
- **Communicate with Collaborators:** Discuss the conflict and reach a consensus, ensuring everyone understands the chosen resolution.

## 3. Work in Pairs: Practice Makes Perfect!
1. Create a New Repository: Work with a partner to create a new git repository on your preferred platform (e.g., GitHub, GitLab).
2. Make Conflicting Changes: Both partners edit the same file, making different modifications to specific lines. Commit and push your changes to separate branches.
3. Merge and Resolve: Create a pull request to merge your branches. Identify the conflict and apply the strategies covered in point 2 to resolve it manually.
4. Push & Verify: Push the resolved changes and verify if the conflict is fixed. Discuss the experience and challenges faced during the process.

## 4. Step-by-Step Conflict Resolution:
1. Identify Conflicts: Run `git status` to see any files marked as conflicted.
2. Examine Changes: Use `git diff` to understand the specific lines and versions in conflict.
3. Edit Locally: Open the conflicting file in a text editor and resolve the overlaps manually.
4. Remove Markers: Delete the conflict markers (usually denoted by `<<<<<<<`, `=======`, and `>>>>>>>`) after merging your desired changes.
5. Stage and Commit: Use `git add` to stage the resolved file and `git commit` to save the changes.
6. Push and Merge: Push your changes to the remote repository and resolve the merge conflict on the platform (e.g., via pull request review).

### Sources & References
- [Atlassian Git Tutorial](https://support.atlassian.com/bitbucket-cloud/docs/resolve-merge-conflicts/)
- [Github Docs](https://docs.github.com/articles/resolving-a-merge-conflict-on-github)
- [Git SCM](https://git-scm.com/docs/)
- [Pro Git Book](https://git-scm.com/book)
>### *Remember, effective communication and a clear understanding of the changes are crucial for successful conflict resolution. Don't hesitate to seek help from colleagues or online resources if needed. Happy merging!*
> *@NaziMv*