# ***Git & GitHub Workshop***

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
4. ***Push changes:*** git push -u origin main


## Task 3: Advanced Git Challenges

### 1. Branching and Merging

- Created new branches: `br1`, `br2`, and `br3`.

- Created changes in a branch.

- Used ***git add .*** to stage the changes.

- Used ***git commit*** to save the changes.

- Merged the changes back into the `main` branch.

### 2. Collaborating with Pull Requests

- Forked a classmate's repository: `Padmaqaauto/github-workshop-practice`.

- Created a change in my fork.

- Created a Pull Request from my branch to the classmate's ***main*** branch.

- Pull Request was created successfully and had no merge conflicts.

### 3. Revert and Reset 

- Created a practice branch: ***git checkout -b revert*** 

- Created a practice file: ***echo revert > revert.txt*** 

- Added and committed the file: ***git add .*** ***git commit -m "add revert"***

 - Used ***git revert*** to undo the commit: ***git revert 8ca90c2*** 

 - Used ***git reset --soft HEAD~1*** to move back one commit: 
 ***git reset --soft HEAD~1*** 

 - Checked the changes:  ***git status*** 

 
  ***git log --oneline -3***

### 4. 🏷️ Tagging and Releases

- Created a tag: ***git tag version1***

- Checked the tag: ***git tag***

- Pushed the tag to GitHub: ***git push origin version1***
 
- Verified the ***version1*** tag on GitHub.