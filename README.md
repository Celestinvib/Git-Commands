# Git Commands

## 🔹 Git Branch Naming
<h4>main or master</h4>
Main branch where stable, production-ready code is always present.
<h4>Develop</h4>
Branch where new features are integrated before moving to main.
<h4>feature/</h4>
Branch for developing a new feature or functionality.
Created from develop and then integrated into develop.
<h4>bugfix/</h4>
Branch for fixing non-urgent bugs.
Created from develop and integrated into develop.
<h4>hotfix/</h4>
Branch for urgent fixes in production.
Created from main and then integrated into main and develop.
Format: hotfix/bug-name
<h4>release/</h4>
Branch for preparing a release for production.
Allows testing and bug fixes before merging to main. Example: release/1.0.0
<h4>test/ or experiment/</h4>
For testing or experimental development.
Example: test/new-api, experiment/prototype-ui

## 🔸 Git Commands

Create a new branch:

    git checkout -b branchname
Search for new branches in the repo

    git fetch
Delete local branch

    git branch -D branchname

Delete remote branch

    git push origin --delete branchname

When you need to pull but have uncommitted changes that don't conflict with the changes:

    git stash (saves changes)
    git pull
    git stash pop (overwrites changes with what was pulled)
Git Bash (Open terminal)

    gitk --all --date-order

![image](https://github.com/user-attachments/assets/504de6c4-64ef-40ef-9e4c-e168077be2f9)


