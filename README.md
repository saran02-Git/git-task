# Git Practice Task

This repository contains a hands-on Git practice task focused on core version control workflows such
as repository setup, branching, merge, rebase, and stash operations.

Task Coverage
• Created a new local working directory and added sample project files.
• Initialized the local directory as a Git repository.
• Created an empty repository on GitHub and linked the local repository to it.
• Pushed the local project files to GitHub.
• Performed merge, rebase, and stash operations.
• Captured output screenshots for each major Git workflow step.

Repository Files
• file1.txt
• file2.txt
• README.md
• screenshots/

Git Workflows Performed
Repository Setup
The following setup was completed:

git init
git remote add origin <repository-url>
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
Branching and Merge
A feature branch was created, updated, and merged back into main.
git checkout -b feature-branch

make changes
git add .
git commit -m "Feature branch changes"
git checkout main
git merge feature-branch

Merge Conflict Handling
A merge conflict was created intentionally and then resolved manually to understand conflict
resolution.
• screenshots/commit in feature branch.png
• screenshots/commit in main.png
• screenshots/Merge.png
• screenshots/Conflict output.png
• screenshots/Conflict resolved.png

Rebase:
Rebase was performed to understand linear commit history and branch integration.
git checkout feature-branch
git rebase main
• screenshots/Rebase.png
• screenshots/rebase output.png
• screenshots/After rebase.png

Stash:
Stash was used to temporarily save local changes and reapply them later.
git stash
git stash list
git stash apply

git stash pop
• screenshots/git stash apply.png
• screenshots/Stashlistapply.png
• screenshots/Git stash-list-pop.png

Screenshots Included
The screenshots folder contains command output evidence for merge, merge conflict creation and
resolution, rebase, stash workflows, and push-related output handling.
