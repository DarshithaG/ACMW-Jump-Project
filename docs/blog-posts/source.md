---
title: Souce Control
sidebar_label: Visual Studio Code
description: The usage of source control in visual studio code
---

# A Beginner's Guide to GitHub

## Introduction
Effective code management, change tracking, and team collaboration all depend on version control.  The most popular version control system, Git, is integrated into Visual Studio Code. 

## Why use Sourse Control?
1. Track Changes: It keeps a history of the changes in code made.
2. Collaboration: Creats a easier base to work with team members.
3. Rollback & Recovery: Shows the previous versions of changes.
4. Branching & Merging: Experiment with new features without affecting the main project.

#### Setting Up Git in VS Code

Open VS Code and Check Git Installation

Open VS Code and launch the terminal  `(Ctrl + `)` and run:
```bash
git --version
```
If Git is installed, you will see the version number. 
Initialize a Git Repository

Navigate to your project folder, initialize a new Git repository and configure Git.
Set up your username and email.

### Using Source Control in VS Code

1. Adding and Committing Changes

Open the Source Control tab.

Click the `+` icon next to each file to stage them.

Type a commit message in the message box.

Click the ✔ Commit button.
2. Connecting to a Remote Repository
Using the Source Control tab will help push changes by clicking the Publish to GitHub button.
(OR)
To push code to GitHub or another remote repository:
```bash
git remote add origin <repository-url>
git branch -M main
git push -u origin main
```
3. Pulling and Pushing Changes
In the source control, ckick the option to pull and push you modifications in the code.
(OR)
Using the following code in the terminal:

To fetch the latest change from the local repossitory
```bash
git pull origin main
```

To push your commits
```bash
git push origin main
```
4. Creating and Switching Branches
Using the Branches section in VS Code’s Source Control tab.

5. Merging Branches
To merge a feature branch into the main branch:
```bash
git checkout main
git merge feature-branch
```
## Conclusions

The Source Control feature in VS Code enables smooth and effective version management. Regardless of whether you're working alone or as part of a team, becoming proficient in Git within VS Code will enhance your development process. 
