# GITPROJECT2

**WHAT IS GIT?**

Git is a distributed version control system designed to track changes in source code during software development. It allows multiple developers to collaborate on a project efficiently, keeping track of changes, managing versions, and enabling easy collaboration.

**Here are some key concepts and features of Git:**

**Version Control System:**

Git tracks changes to files over time, allowing you to revert to previous versions, compare changes, and collaborate effectively with others.

**Distributed:**

Unlike centralized version control systems, Git is distributed. Each developer has a complete copy of the repository, which makes branching, merging, and working offline much easier.

**Repositories:**

A Git repository is a collection of files, their history, and the configuration data needed to manage them. It stores all versions of files and their metadata.

**Commits:**

A commit represents a snapshot of the changes made to the repository at a specific point in time. Each commit has a unique identifier and includes a message explaining the changes made.

**Branches:**

Git allows you to create branches, which are independent lines of development. This feature enables you to work on different features or bug fixes simultaneously.

**Merging:**

Merging combines changes from one branch into another. Git automatically handles merging whenever you integrate changes from one branch into another.

**Pull Requests:**

Pull requests (PRs) are a way to propose changes to a repository. They allow collaborators to review, discuss, and approve the changes before they are merged.

**Remote Repositories:**

Git supports remote repositories hosted on platforms like GitHub, GitLab, and Bitbucket. Developers can push their changes to remote repositories and pull changes made by others.

**Clone:**

Cloning creates a copy of a remote repository on your local machine. This allows you to work on the project locally and push your changes back to the remote repository.

**Push and Pull:**

Pushing involves sending your local changes to a remote repository, while pulling involves fetching changes from a remote repository to update your local copy.

**Conflict Resolution:**

Git helps manage conflicts that can arise when multiple developers modify the same file. It provides tools to resolve these conflicts manually.

Git is widely used in the software development industry due to its flexibility, speed, and powerful branching and merging capabilities. It helps teams manage complex projects efficiently and maintain a history of changes, making collaboration and tracking progress easier.

Here's a step-by-step guide on how to initialize a repository and make a commit using Git Bash:

**Install Git Bash (if not already installed):**

If you haven't already, download and install Git Bash from the official Git website: https://git-scm.com/downloads

**Open Git Bash:**

Once installed, open Git Bash. You'll be working with a command-line interface.


![GIT BASH TERMINAL](https://github.com/Ukdav/GITPROJECT2/assets/139593350/1aa14ee6-b97c-4223-ae14-a8aa03de4952)


**Navigate to Your Project Directory:**

On your terminal, create a working folder or directory e.g DevOps using this command **Mkdir DevOps**

Use the cd command to navigate to the directory where you want to create your Git repository. For example: **cd DevOps**

while you are inside the folder, run this command: **git init**

![mkdir   cd   git init](https://github.com/Ukdav/GITPROJECT2/assets/139593350/b74b837f-f31a-40d8-bd66-cbad10fb3581)

**Make your first commit command:**

In the last section, we successfully created our working directory and initialized a Git repository. Now we would make our first commit.

Before making our first commit, let's try and understand what a commit is in Git. Commit is more or less saving the changes you made to your files; changing can be adding, modifying or deleting files or text.

When you make a commit, Git takes a snapshot of the current state of your repository and saves a copy in the git folder inside your working directory.

Now let us make our first commit by following the below steps:

1. Inside your working directory, create a file index.txt with this command: **touch index.txt**
2. Write a sentence of your choice inside the text.txt file, afterward save your changes.
3. Add your changes to the git staging area using this command: **git add.**
4. To commit your changes to git, run this command: **git commit -m "initial commit"**

Also, bear in mind that the **-m** is also used to provide a commit message, the commit message is a nice way to provide context about the commit. when writing a commit message, make it as descriptive as possible, let it explain why the commit was done.

   ![toach and git add](https://github.com/Ukdav/GITPROJECT2/assets/139593350/ad8dab72-d075-47ff-8920-0bd0c8a42ade)

   ![commit](https://github.com/Ukdav/GITPROJECT2/assets/139593350/195464e7-b2bf-48a8-b1c0-83618ba19296)

   **Working with Branches**

   Imagine you have a notebook and you want to write different stories on different pages of your notebook so that you do not mess up your previous note.

   Git branch helps you create a different copy (page) of your source code. in your new branch you can make changes as you please, your changes is independent of what is available in the main copy.

   Git Branch is commonly used to develop new feature of your application, you will agree with me that the initial code is untested and such can nit be added to the code base of your live application.

   Git branch is also an important tool for collaboration within remote teams (developers working from different locations). They can make separate branches while working on the same feature, And at the end of the day, coverage their code to one branch.

   Make your first git branch:

   To make a new branch run the command: **git checkout -b**

   The -b flags help you create and changes to the new branch

   with that said let's make our first branch following these steps.

   1. Having made your first commit in the previous lesson
   2. Make a new branch by running this command: **git checkout -b my-new-branch**
   3. List your git branches using this command: **git branch**
   4. To change into an existing or old branch use this command: git checkout main

![create new branch](https://github.com/Ukdav/GITPROJECT2/assets/139593350/3a749b19-b006-4fb2-8ca1-097f0e24a838)

**Merging a branch into another branch**

Let's say we have two branches A and B. and we want to add the content of Branch B into A using command: **git merge B**

![merge b and A](https://github.com/Ukdav/GITPROJECT2/assets/139593350/349d2199-d108-4b39-8621-71976aa3da6b)

**Deleting a git branch**

When a new feature is added to an application, it's often done in a feature branch. usually, this feature branch is deleted when the code must have a tested and merged into a staging or dev. environment depending on the branch strategy of the team.

Git branch can be deleted with commands: **git branch -d <branch_name>**

![delete branch](https://github.com/Ukdav/GITPROJECT2/assets/139593350/25c807cc-5faf-491a-9616-54ed799af036)

This is by no means all that you can do with branches in Git. To learn more type the command Git branch --help on your terminal

**Collaboration and Remote Repositories**

GitHub is a web-based platform where git repositories are hosted. by hosting our local Git repository on Git Hub. It becomes available on the public internet (it is possible to create a private repository as well). Anyone can now access it.

The remote team can now view, update, and make changes to the same repository.

**Pushing your local GIT Repository to your remote GitHub Repository**
In our previous chapter, we have writing our story in our local git repository. Our friend is interested in contributing to our story but he is unable to do so because we currently have our story locally in our machine.

Having created a GitHub account and a GitHub repository in earlier steps, let's send a copy of our story to our repository on GitHub

We will achieve this by following the steps below:

1. Add a remote repository to the local repository using the command below: **git remote add origin <link to your github repo>**











   
   

   

   



















