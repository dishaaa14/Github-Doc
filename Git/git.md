# Table of Contents
**What is Version Control?**.............................................	  2
Here’s Why:..........................................................	 2
Difference between Git and GitHub....................................	 2
Understanding Sections of a Git Project.............................. 	2
**How to push a repository to GitHub**....................................	4
Step 1 – Create a GitHub account......................................	4
Step 2 – Fork the repository..........................................	4
Step 3 – Cloning a Git Repo:...........................................	4
Add files to the Staging Area for commit:..............................	4
How to commit files in Git............................................	5
Before we commit let’s see what files are staged:.....................	5
Commit Changes you made to your Git Repo:.............................	5
Uncommit Changes you just made to your Git Repo:......................	5
Revert back to the last committed version to the Git Repo:............	6
View Commit History:..................................................	6
How to Pull a Repository in Git.......................................	7
Here are two more useful git commands:................................	7
Additional Reading:...................................................	8
Git Ignore:...........................................................	8
How to Use Branches in Git............................................	8


## What is Version Control?
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. So ideally, we can place any file in the computer on version control.

Here’s Why:

A Version Control System (VCS) allows you to revert files back to a previous state, revert the entire project back to a previous state, review changes made over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Using a VCS also means that if you screw things up or lose files, you can generally recover easily.

## What is Git?

Git is a version-control system for tracking changes in computer files and coordinating work on those files among multiple people. Git is a Distributed Version Control System. So Git does not necessarily rely on a central server to store all the versions of a project’s files. Instead, every user “clones” a copy of a repository (a collection of files) and has the full history of the project on their own hard drive. This clone has all of the metadata of the original while the original itself is stored on a self-hosted server or a third-party hosting service like GitHub.

## Difference between Git and GitHub


Git and GitHub are two different things. Git is the version control system, while GitHub is a service for hosting Git repos that helps people collaborate on writing software. 

**## Understanding Sections of a Git Project**


What is a Repository?
A repository a.k.a. repo is nothing but a collection of source code.

![WorkFlow of Git](https://cdn-media-1.freecodecamp.org/images/1*iL2J8k4ygQlg3xriKGimbQ.png)

A Git project will have the following main sections:
1.	The Git directory is where Git stores everything it needs to accurately track the project. This includes metadata and an object database which includes compressed versions of the project files.

2.	The working directory is where a user makes local changes to a project. The working directory pulls the project’s files from the Git directory’s object database and places them on the user’s local machine.
If you consider a file in your Working Directory, it can be in three possible state.
•	It can be staged. This means the files with the updated changes are marked to be committed to the local repository but not yet committed.
•	It can be modified. This means the files with the updated changes are not yet stored in the local repository.
•	It can be committed. This means that the changes you made to your file are safely stored in the local repository.


3.	 The staging area is a file (also called the “index”, “stage”, or “cache”) that stores information about what will go into your next commit. A commit is when you tell Git to save these staged changes. Git takes a snapshot of the files as they are and permanently stores that snapshot in the Git directory.

## How to push a repository to GitHub
I will divide this section into steps to help you understand the process more clearly.

### Step 1 – Create a GitHub account
To be able to use GitHub, you will have to create an account first. You can do that on the website:
[http://github.com/](http://github.com/)

### Step 2 – Fork the repository
Click on the Fork button ![fork](https://user-images.githubusercontent.com/55580805/161741123-02a2fd74-1c33-409b-8c58-8265c7fa3812.png)
to copy the repository to your account. This will be essential for deployment to heroku. 

### Step 3 – Cloning a Git Repo:
Locate to the directory you want to clone the repo: 
[https://github.com/orgs/BetsolLLC/repositories](https://github.com/orgs/BetsolLLC/repositories)

Copy the link of the repository you want and enter the following:






