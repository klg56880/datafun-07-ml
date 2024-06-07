# datafun-07-ml
module 7 project

## Overview
In this Module 7 project, I will utilize machile learning to build a model, make predictions, visualize the model, and publish insights. 

## How to Install and Run the Project

## Create Project
Created a new repo in GitHub with the name 'datafun-06-EDA' 

Added the default README.md 

Named the script "karitaylor_eda.ipynb"

## Cloned project down to my machine
Opened VS Code 

Used file > open folder to access the folder where I want my project to reside

Opened a new terminal (with powershell as default) 

Used the 'git clone' command to clone the project to my machine

```shell

git clone site_URL

```

## Created and activated a Python virtual environment
Used the following command to create a virtual environment:
```shell

py -m venv .venv

```
Used the following command to activate the virtual environment:
```shell

.\.venv\Scripts\Activate.ps1

```

## Created a requirements.txt file
Created a new file in the root project folder labeled requirements.txt

Listed the required external dependencies in this file

## Installed external dependencies in the requirements.txt file and froze
Installed dependencies using the following command:
```shell

py -m pip install jupyterlab pandas pyarrow matplotlib seaborn

```
Froze the requirements.txt file using the following command:
```shell

py -m pip freeze > requirements.txt

```

## Created .gitignore
Created a new file in my datafun-05-sql-project folder named .gitignore

Typed .venv/ into line 1

Typed .ipynb_checkpoints/ into line 2

## Git add and commit changes
Git add and commit my initial changes with the following commands:
```shell

git add .
git commit -m "initial commit"

```

## Git push changes to GitHub
Git push your initial changes to GitHub with the following command:
```shell

git push origin main

```
