# GitHub-Git-Commands-Guide
A comprehensive guide to GitHub and Git commands, including when and how to use them. This repository serves as a 
resource for both beginners and advanced users to understand the various Git commands and their applications in version
control and repository management.

### Table of Contents: (Click to navigate)
- [What is Git?](#what-is-git)
- [What is GitHub?](#what-is-github)
- [Configuring Git](#configuring-git)
- [Basic Git Commands](#basic-git-commands)

### What is Git?
Git is a distributed version control system that allows multiple developers to work on the same project simultaneously. 
It tracks changes made to files and directories, enabling developers to collaborate effectively and manage the 
project's history efficiently.

### What is GitHub?
GitHub is a web-based platform that provides hosting services for Git repositories. It allows developers to store,
manage, and share their code with others. GitHub offers features such as issue tracking, pull requests, and collaboration
tools to streamline the development process. It is widely used by open-source projects and software development teams.


### Configuring Git:
* Install Git on your system.
    ```bash
    sudo apt-get install git
    ```
* Configuring User information used across all local repositories.
    ```bash
   git config -l
    ```
  It is used to list all the configurations that are set in the Git repository.


* Set the username for the Git repository.
    ```bash
    git config --global user.name "Your Full Name"
    ```
* Set the email address for the Git repository.
    ```bash
    git config --global user.email "Email Address"
    ```

```git config --global color.ui auto
```


### Basic Git Commands:
* git init Initializes a new Git repository.
    ```bash
    git init
    ```
* Add files to the staging area.
    ```bash
    git add .
    ```
* Add a specific file to the staging area.
    ```bash
    git add <file_name>
    ```
* Review the changes made to the files.
    ```bash
    git status
    ```
* Commit the changes to the repository.
    ```bash
    git commit -m "Commit message"
    ```
* check the commit history.
    ```bash
    git log
    ```
* Rollback to a previous commit.
    ```bash
    git reset --hard
    ```
  or, to a specific commit. here `<commit_id>` is the commit id of the commit to which you want to rollback.
    ```bash
    git reset --hard <commit_id>
    ```
* Push the changes to the remote repository.
    ```bash
    git push
    ```
