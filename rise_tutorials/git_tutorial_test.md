# Git for Medical Imaging and Research

## Introduction to Git

### What is Git?
Git is a distributed version control system that helps track changes in code and collaborate effectively. It is widely used in research, software development, and medical imaging projects.

### Why Learn Git for Medical Imaging?
- **Version Control**: Track changes in code and data
- **Collaboration**: Work with multiple researchers
- **Reproducibility**: Ensure research integrity

### Installing Git
To install Git, follow these steps:
```sh
# For Ubuntu/Debian
sudo apt update
sudo apt install git

# For macOS
brew install git

# For Windows
Download and install from https://git-scm.com/
```

---
## Basic Git Commands

### Configuring Git
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Initializing a Repository
```sh
git init my_project
cd my_project
```

### Cloning a Repository
```sh
git clone https://github.com/user/repo.git
```

### Checking Status
```sh
git status
```

### Staging and Committing Changes
```sh
git add filename.py
git commit -m "Initial commit"
```

---
## Branching and Merging

### Creating a Branch
```sh
git branch new-feature
git checkout new-feature
```

### Merging Branches
```sh
git checkout main
git merge new-feature
```

---
## Working with Remote Repositories

### Adding a Remote Repository
```sh
git remote add origin https://github.com/user/repo.git
```

### Pushing to Remote
```sh
git push origin main
```

### Pulling Changes
```sh
git pull origin main
```

---
## Undoing Changes

### Reverting a Commit
```sh
git revert commit_id
```

### Resetting Changes
```sh
git reset --hard commit_id
```

---
## Chapter 6: Collaboration with GitHub

### Forking a Repository
Go to a repository on GitHub and click **Fork**.

### Creating a Pull Request
1. Make changes in a new branch
2. Push the branch to your GitHub repository
3. Open a Pull Request from GitHub UI

---

This structured tutorial serves as a beginner-friendly introduction to Git, tailored for medical imaging and research applications at MICCAI. More advanced topics like Git workflows and CI/CD can be covered in future sections.

