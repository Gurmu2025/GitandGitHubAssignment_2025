#  Git & GitHub Assignment

This repository was created as part of **Assignment 1: Git & GitHub**.  
It demonstrates how to create, manage, and synchronize local and remote Git repositories.  
All major Git operations, including initialization, staging, committing, pushing, and creating a professional README file, have been performed in this project.

---

## Git & GitHub Assignment Guide (With Full Details)
STEP 1 — Create Your Folder
1. Go to your Desktop or Documents.
2. Create a new folder named: GitAndGitHub_Assignment_2025
3. Open the folder.
Inside the folder, create a file called sample_data.py.
Paste this inside it:
print("Sample data script for my Git & GitHub Assignment 2025")
STEP 2 — Open Git Bash Inside the Folder
Right-click inside the folder → select “Git Bash Here”.

Git Bash should open with a path similar to:
username@DESKTOP MINGW64 ~/Desktop/GitAndGitHub_Assignment_2025

If not, close Git Bash and right‑click again to ensure you're inside the correct folder.
STEP 3 — Set Your Git Identity (Required Once Only)
Set your global Git identity using your real GitHub username and email:

git config --global user.name "username"
git config --global user.email "email.com"

To check whether your identity is already set, run:
git config --global user.name
git config --global user.email

You should see:
user name
Email

If you don’t see these values, repeat the commands above.
STEP 4 — Initialize Git in Your Folder
Run:
git init

This creates a hidden .git folder where Git tracks all your project data.
You will see a message:
Initialized empty Git repository in .../.git/
STEP 5 — Add Files and Make Your First Commit
Add all files:
git add .

Check what’s staged (optional):
git status

Then commit:
git commit -m "Add sample data script"

This is your FIRST commit. 
STEP 6 — Create Your GitHub Repository
1. Log into GitHub (https://github.com)
2. Click **New Repository**
3. Repository name: GitAndGitHub_Assignment_2025
4. Visibility: Public
5. DO NOT check boxes for README, .gitignore, or License
6. Click Create Repository

Your repository URL will look like:
https://github.com/username/GitAndGitHub_Assignment_2025.git

STEP 7 — Connect Local Git to GitHub
Run this command to connect your local folder to GitHub:
git remote add origin https://github.com/Username/GitAndGitHub_Assignment_2025.git

Then push your project for the first time:
git branch -M main
git push -u origin main

If GitHub asks for a password, use a Personal Access Token (PAT).
STEP 8 — Create README.md (Professional Format)
Create a new file in your project folder called README.md and paste:

# Git & GitHub Assignment (2025)
STEP 9 — Commit and Push README.md
Add the README:
git add README.md

Commit it:
git commit -m "Add professional README.md file"

Push:
git push



---

## Repository Contents

| File Name | Description |
|------------|--------------|
| `sample_data.py` | A simple Python script used as sample data for the assignment. |
| `README.md` | This document describes the project details and outlines the Git workflow steps. |

---

## Sample Script Description

The `sample_data.py` file contains a very simple Python code that prints a text message, demonstrating the ability to add and commit files in a repository.

**Code:**
```python
# sample_data.py
# GitandGitHubAssignment_2025
# GitandGitHubAssignment_2025
