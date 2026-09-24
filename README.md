# Title:***Git & GitHub Workshop***

## Description:

This is my practice project for Git and GitHub. I will learn Git commands and practice working with repositories, commits, branches, and pushing changes to GitHub.

## Task 1: The Basics

In this task, I will create a ***New Git repository***, make my first commit, connect it to GitHub, track changes, and push my work to GitHub.

### Steps to Reproduce:

### 1. Initialize a New Repository

1. ***git init***- Creates a new Git repository in my project folder.

2. ***git status*** – See repository status

3. ***Create README.md*** – Creates the README file.

### 2. Connect to GitHub

1. Create and connect a GitHub repository.

 2. ***git remote add origin <repository-url>*** – Connects to GitHub.

3. ***git remote -v*** – view the remote repository.

    
### 3. Track Changes

1. ***git status*** – See changes.

2. ***git add task1.txt and task2.txt*** – Stages the file.

3. ***git commit -m "updates note"*** – Saves the staged changes to the local Git repository

4. ***git push -u origin main*** – Pushes changes to GitHub.

### 4. Ignoring Files

1. ***.gitignore***  -Tells Git which files should not be tracked.

2. ***echo Name=ezhil > .gitignore ***  -Adds to the ignore list.

3. ***git add .gitignore***  -Stages the .gitignore file.

4. ***git commit -m "Add .gitignore"***  -Saves the changes.

5. ***git push***  -Pushes the changes to GitHub.

## Task 2: Clone, Rename, and Re-Publish 

***Clone the repository:***
 git clone https://github.com/Lexicon-Smaland/Hello-World.git

 ***Change the remote:*** git remote set-url origin https://github.com/Ezhilarasi28/Gitclone.git

1. ***Edit README.md***

2. ***Add changes:*** git add .
3. ***Commit changes:*** git commit -m "Update README"
4. ***Push changes:***git push -u origin main

