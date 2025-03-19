---
title: Virtual Environment
sidebar_label: Virtual Environment
description: How to create venv in vscode
---

# Creating virtual environmnent in Visual Studio Code

## Introduction 
In Python projects, maintaining dependencies requires a virtual environment, or venv.  VS Code ensures that your project remains separate from system-wide packages by making the creation and use of venvs simple. When you install packages into a virtual environment it will end up in this new folder, and thus isolated from other packages used by other workspaces.

## Why use Virtual Environment?
> Dependency Management: In many different Python projects, this helps avoid conflicts.
> Reproducibility: They help ensure the different environment are consistent across the projects.
> Isolation: THis help prevents unnecessary errors from cluttering your global Python installation.

## How to Cceate a Virtual Environment in VS Code
1. Open your project folder in VS Code
- Navigate to your project directory and open it in VS Code
2. . Create a virtual environment
Open the command palette by pressing `Ctrl+Shift+P`.
Type: Create Environment and select it
- Choose venv
- As the base select the interpreter you want for your virtual environment.
3. To activate the virtual environment
Once the environment is created, VS Code will prompt you to select it for your workspace. Click Yes.
(0R)
3. Run the command `python -m venv venv` in the terminal.