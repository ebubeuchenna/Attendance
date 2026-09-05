1. What is Git?
Git is a tool that keeps track of changes in your files.
For example, if you are making a website and change something by mistake, Git can help you see what changed and go back to an earlier version.
Git works on your own computer, so you do not need the internet to use basic Git commands.

2. What is GitHub?
GitHub is a website where Git repositories can be stored online.
The simple difference is:
Git = the tool that tracks your project.
GitHub = an online place where you can store and share the project.

3. What does git init do?
When you type:
git init
Git starts tracking the folder.
It creates a hidden folder called .git.
The .git folder contains important information about your Git history.

4. The three areas in Git
Git has three important areas:
Working Directory
This is where you actually work on your files.
Staging Area
This is where you put the changes you want to include in your next commit.
You do this with:
git add
Git Repository
This is where Git permanently saves your commits and their history.
You do this with:
git commit

5. What does git status do?
git status tells you what is happening in your project.
It can tell you things like:
Which files were changed
Which files are new
Which files are ready to be committed

6. What does git add do?
Suppose you created a file called index.html.
If you type:
git add index.html
you are telling Git:
"I want this file included in my next commit."

7. What does git commit do?
A commit is like a saved version of your project.
For example:
git commit -m "Add homepage"
This tells Git to save the staged changes with the message "Add homepage."

8. What does git log do?
git log shows your previous commits.
It is basically a record of the changes you have saved in Git.

9. git add index.html vs git add .
git add index.html
Stages only index.html.
git add .
Stages all eligible changed files in the current directory and its subdirectories.
So, one is for a specific file, while the other can stage many files.

10. Why are commit messages important?
A good commit message should clearly explain what you changed.
Bad:
fix stuff
Good:
Fix mobile navbar toggle button responsiveness on iOS Safari
Good messages help other people understand the project's history and make it easier to find specific changes later.
The most important commands to remember
git status — check what changed
git add — prepare changes
git commit — save changes
git log — see previous commits

