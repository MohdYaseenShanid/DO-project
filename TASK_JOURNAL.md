# Task 4 Journal: Version-Controlled Project

This document outlines the steps taken to complete the Git version control task.

## 1. Project Initialization
- Created a local directory `devops-git-project`.
- Initialized a Git repository using `git init`.
- Created `app.py`, `.gitignore`, and `README.md`.
- Pushed the initial commit to a new GitHub repository.

## 2. Branching Strategy
- Established a `main` branch for stable releases and a `dev` branch for integration.
- Created the `dev` branch and pushed it to remote.

## 3. Feature Development
- Created a new branch `feature/add-user-greeting` from `dev`.
- Modified `app.py` to add new functionality.
- Committed and pushed the feature branch.

## 4. Pull Request Workflow
- Opened a Pull Request from `feature/add-user-greeting` to `dev`.
- Merged the PR after review and deleted the feature branch.
- Synced the local `dev` branch.

## 5. Release and Tagging
- Created a Pull Request from `dev` to `main` to simulate a release.
- Merged the release PR.
- Created and pushed an annotated tag `v1.0.0` to mark the release.