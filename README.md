# CS615C-lab1
# Git Basics

This README provides instructions for basic Git operations to help you get started with version control.

## **1. Git Setup**

### **Install Git:**
- Download and install Git from [git-scm.com](https://git-scm.com/)

### **Configure Git:**
```sh
# Set user name and email
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## **2. Initializing a Repository**
```sh
# Create a new repository in the current directory
git init
```

## **3. Cloning a Repository**
```sh
# Clone an existing repository
git clone <repository_url>
```

## **4. Staging and Committing Changes**
```sh
# Check the status of your working directory
git status

# Add specific files to the staging area
git add <file>

# Add all changes to the staging area
git add .

# Commit the staged changes with a message
git commit -m "Your commit message"
```

## **5. Viewing Commit History**
```sh
# View commit history
git log
```

## **6. Branching and Merging**
```sh
# List all branches
git branch

# Create a new branch
git branch <branch_name>

# Switch to a branch
git checkout <branch_name>

# Create and switch to a new branch
git checkout -b <branch_name>

# Merge a branch into the current branch
git merge <branch_name>
```

## **7. Pushing and Pulling Changes**
```sh
# Push changes to a remote repository
git push origin <branch_name>

# Pull the latest changes from a remote repository
git pull origin <branch_name>
```

## **8. Working with Remote Repositories**
```sh
# Add a remote repository
git remote add origin <repository_url>

# View remote repositories
git remote -v
```


This guide provides an overview of essential Git commands to get started with version control efficiently.
