# Week 4: Git & GitHub Advanced Challenge

## Project Overview

This project was completed as part of the 90 Days of DevOps challenge. The goal was to gain hands-on experience with Git and GitHub by practicing repository management, commits, branching strategies, pull requests, and SSH authentication.

The project demonstrates a complete Git workflow used in real-world software development environments.

---

## Skills Covered

* Git Repository Management
* GitHub Forking
* Cloning Repositories
* Git Initialization
* Staging and Committing Changes
* Viewing Commit History
* Branch Creation and Management
* Feature Branch Workflow
* Pull Requests (PR)
* Branch Merging
* SSH Authentication with GitHub
* Documentation and Collaboration

---

## Technologies Used

* Git
* GitHub
* Linux
* SSH

---

## Repository Structure

```text
week-4-challenge/
├── info.txt
├── solution.md
└── screenshots/
    ├── 01_repository_cloned.png
    ├── 01_repository_forked.png
    ├── 02_week-4-challenge_created.png
    ├── 03_first_commit_created.png.png
    ├── 04_first_push_to_github.png
    ├── 04_first_push_to_github_terminal.png
    ├── 05_git_log_history.png
    ├── 06_feature_branch_created.png
    ├── 07_solution_documentation_added.png
    ├── 08_ssh_authentication_configured.png
    ├── 09_create_pull_request.png
    ├── 10_open_PR_page.png
    ├── 11_PR_created_successfully.png
    ├── 12_GIthub_PR_remote_merged.png
    └── 13_Terminal_pull_request_merged.png
```

---

## Project Workflow

### 1. Fork Repository

Forked the challenge repository to my GitHub account.

### 2. Clone Repository

Cloned the forked repository to a local Linux machine.

### 3. Create Challenge Directory

Created a dedicated directory for the Week 4 challenge and initialized a Git repository.

### 4. Create and Commit Files

Created `info.txt`, staged changes, and made the initial commit.

### 5. Push to GitHub

Configured the remote repository and pushed local commits.

### 6. Explore Commit History

Used Git commands to inspect and analyze commit history.

### 7. Branching Workflow

Created a feature branch called `feature-update` and made changes independently from the main branch.

### 8. Documentation

Created `solution.md` documenting commands used and lessons learned.

### 9. SSH Authentication

Verified GitHub authentication using SSH keys and performed Git operations securely.

### 10. Pull Request Workflow

Created a Pull Request, reviewed changes, merged the feature branch into the main branch, and cleaned up the branch.

---

## Git Commands Practiced

```bash
git clone
git init
git status
git add
git commit
git log
git show
git branch
git switch
git push
git pull
git remote
git merge
git branch -d

ssh-keygen
ssh-add
ssh -T git@github.com
```

---

## Why Branching Strategies Matter

Branching strategies are important because they allow developers to work on features, bug fixes, and experiments without affecting the main codebase.

Benefits include:

* Isolating features and bug fixes
* Supporting parallel development
* Reducing merge conflicts
* Enabling code reviews through Pull Requests
* Improving collaboration between team members

This workflow is widely used in DevOps and software development teams.

---

## Screenshots

### Repository Setup

* 01_repository_forked.png
* 01_repository_cloned.png

### Git Repository Initialization

* 02_week-4-challenge_created.png

### Initial Commit

* 03_first_commit_created.png.png

### GitHub Push

* 04_first_push_to_github.png
* 04_first_push_to_github_terminal.png

### Commit History

* 05_git_log_history.png

### Branching

* 06_feature_branch_created.png

### Documentation

* 07_solution_documentation_added.png

### SSH Authentication

* 08_ssh_authentication_configured.png

### Pull Request Workflow

* 09_create_pull_request.png
* 10_open_PR_page.png
* 11_PR_created_successfully.png
* 12_GIthub_PR_remote_merged.png
* 13_Terminal_pull_request_merged.png

---

## Learning Outcomes

Through this project I gained practical experience with:

* Managing repositories using Git
* Working with GitHub forks
* Tracking project history through commits
* Using feature branches for development
* Creating and merging Pull Requests
* Authenticating securely using SSH
* Following collaborative development workflows

---

## Author

Sriram Ganesh

Learning DevOps through hands-on projects and the 90 Days of DevOps challenge.
