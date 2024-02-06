# **Day 1: Introduction to Version Control and Git Basics**
Version control is a system that records changes to files over time, allowing you to recall specific versions later. It enables multiple users to collaborate on a project simultaneously by managing modifications, tracking revisions, and facilitating the merging of different versions. This process enhances collaboration, facilitates error correction, and provides a history of changes made to the project. Git and Subversion are common examples of version control systems used in software development.[More](https://www.perforce.com/blog/vcs/what-is-version-control)

# Install Git
Git is supported almost on all OSs.
+ Windows
  - Download & install binary file[Download latest](https://github.com/git-for-windows/git/releases/download/v2.43.0.windows.1/Git-2.43.0-64-bit.exe)
  - ```
    git version
    ```
+ Linux
  - Debian based distros
    - ```
      apt update
      apt -y install git
      git version
      ```
  - RHEL based distros
    - ```
      yum update
      yum -y install git
      git version
      ```
+ MacOS
  - ```
    brew install git
    git version
    ```
### Get started with basic commands
_**Initialize a Git Repository:**_

Use `git init` in your project directory to initialize a new Git repository. This command sets up the necessary files and directories for version control e.g `.git/`.

_**Add Files to the Staging Area:**_

Use `git add <filename>` to add specific files to the staging area. This tells Git to track changes in these files.
Alternatively, you can use `git add .` to add all files in the current directory and its subdirectories.

_**Commit Changes:**_

Once you've added files to the staging area, commit them using `git commit -m "Commit message"`. This command creates a snapshot of the changes in the repository along with a descriptive message explaining the changes made.

## [Useful video to understand the basics](https://youtu.be/e9lnsKot_SQ)
