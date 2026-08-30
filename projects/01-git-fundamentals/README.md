# Project 01 - Git Fundamentals

## Objective
Demonstrate practical knowledge of core Git workflows, repository initialization, branching strategies, commit history inspection, and remote synchronization.

## Detailed Module Notes

### 1. Initializing a Git Repository
- `git init`: Transforms an existing directory into a Git version-controlled repository by creating a hidden `.git` directory.
- **Working Tree vs. Staging Area:** 
  - *Working Directory:* Where files are created and edited.
  - *Staging Area (Index):* The intermediate layer where changes are staged using `git add` before committing.
  - *Repository (.git):* Stores the committed snapshots permanently.

### 2. Inspecting Repository History (`git log`)
- `git log`: Shows full commit history including Commit Hash, Author, Date, and Message.
- `git log --oneline`: Displays a simplified view with abbreviated commit hashes and titles.
- `git log --graph --all --oneline`: Renders a visual representation of branch merges and development history.

## Mastered CLI Commands
- `git init`
- `git status`
- `git add <file>` / `git add .`
- `git commit -m "message"`
- `git log --oneline`
- `git checkout -b <branch-name>`
- `git remote add origin <url>`
- `git push -u origin <branch-name>`

## Status
In Progress — Reviewing core modules and documenting hands-on labs.
