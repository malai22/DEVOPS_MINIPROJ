# DEVOPS_MINIPROJ

🧩 Team Git Repository Simulation
📘 Project Overview

This project demonstrates a team-based Git workflow using GitHub.
It simulates a collaborative environment where multiple users create branches, make commits, and push changes to a shared repository.

🎯 Objectives

Learn how to create and manage a GitHub repository.

Create multiple branches for different purposes.

Understand how different users can collaborate using Git.

Perform commits and push changes to remote branches.

👥 Team Members
User	Role	GitHub Username
User 1	Project Lead	@user1
User 2	Feature Developer	@user2
User 3	Bug Fixer	@user3
🔧 Steps Followed
1️⃣ Repository Creation

User 1 created a new repository on GitHub named team-git-simulation.

Initialized the repository with a README.md file.

Shared repository access with User 2 and User 3 (added them as collaborators).

# Repository URL Example
https://github.com/user1/team-git-simulation.git

2️⃣ Branch Setup

The default branch main was automatically created.

User 1 created two additional branches using the commands below:

git branch feature
git branch bugfix
git push origin feature
git push origin bugfix


Now the repository contains:

main

feature

bugfix

3️⃣ Individual Contributions

Each user cloned the repository and worked on their own branch.

🧑‍💻 User 1 (Main Branch)
git clone https://github.com/user1/team-git-simulation.git
cd team-git-simulation
git checkout main
# Made some initial setup changes
git add .
git commit -m "Initial setup and readme update"
git push origin main

🧑‍💻 User 2 (Feature Branch)
git clone https://github.com/user1/team-git-simulation.git
cd team-git-simulation
git checkout feature
# Added a new feature file
git add .
git commit -m "Added feature implementation"
git push origin feature

🧑‍💻 User 3 (Bugfix Branch)
git clone https://github.com/user1/team-git-simulation.git
cd team-git-simulation
git checkout bugfix
# Fixed a sample bug
git add .
git commit -m "Fixed issue in code"
git push origin bugfix

4️⃣ Committing Changes

Each user made changes and committed their work to their respective branches.

Example commit commands:

git add <filename>
git commit -m "Description of changes"
git push origin <branch-name>


After this step, all three branches (main, feature, bugfix) have commits from the respective users.
