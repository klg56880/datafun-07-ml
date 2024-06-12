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

## Create final project Jupyter Notebook
Add a new file in your root project folder named "FirstnameLastname_ml.ipynb"

## Use approrpiate markdowns to display project title, author, introduction, and section headings
Level 1 markdown: title
Level 2 markdown: author, introduction, and part 1, 2, and 3 section headings
Level 3 markdown: dependencies section, subsections of part 1, 2, and 3

## Add dependencies
Upload initial dependencies, and add additional dependencies to this section when prompted

## Complete part 1
Follow instructions in chapter 10.16 of the textbook 'Intro to Python for Computer Science and Data Science' to chart a straight line of Celcius and Fahrenheit temperatures

## Complete part 2
Continue to follow instructions in chapter 10.16 of the same textbook, utilizing spicy.stats module's linregress function and seaborn's regplot function to predict and plot future January high temps in NYC. Include subsections titled:

Section 1 - Data Acquisition
Section 2 - Data Inspection
Section 3 - Data Cleaning
Section 4 - Descriptive Statistics
Section 5 - Build the Model
Section 6 - Predict
Section 7 - Visualizations

## Complete part 3
Follow instruction in chapter 15.4 of the textbook to continue analysis of this data. Part 3 will utilize the linear regression estimator from the scikit-learn model to predict future high temps in January in NYC, and a combination of seaborn and matplotlib to plot this data and regression line. Include the following subsections:

Section 1 - Build the Model
Section 2 - Test the Model
Section 3 - Predict
Section 4 - Visualizations

## Complete part 4
Provide insights into the linear regression results provided by each of the two methods. Compare and contrast the two and argue in favor of your preferred method.

## Periodically add, commit, and push changes to github
Use the following commands to add, commit, and push changes to your online repo:
```shell

git add .
git commit -m "commit message"
git push origin main

```
