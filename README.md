# Repository Creation and Basic Git Commands Activity 3

> **Disclaimer:** This activity is for school/educational purposes only.

## Project Details
* **Course:** System Design and Analysis
* **Activity:** Repository Creation and Basic Git Commands Activity 3
* **Name:** Charlize Mira Sarne

Here is the sequential list of all Git commands I used during this activity:

1. **Repository Setup & Configuration**
   - `git init` - Initialized a local Git repository
   - `git remote add origin <URL>` - Connected the local repository to GitHub
   - `git config --global credentials.username "username"` - Configured the username
   - `git config --global user.name "name"` - Configured the author name
   - `git config --global user.email "email"` - Set the Git commit email address

2. **Staging & Committing**
   - `git add .` (or `git add git activity.txt`) - Staged file changes for commit
   - `git commit -m "commit message"` - Saved staged changes to the local commit history
   - `git status` - Checked the status of tracked and untracked files

3. **Creating & Branching**
   - `git checkout -b feature-branch` - Created and switched to a new feature branch
   - `git branch` - Helps to verify branch user location

4. **Merging Branches**
   - `git checkout main` - Switched back to the main branch
   - `git merge feature-branch` - Merged changes from `feature-branch` into `main`

5. **Syncing with GitHub**
   - `git push origin main` - Uploaded local `main` branch commits to GitHub
   - `git pull origin main` - Downloaded and merged remote changes from GitHub into the local repository
   - `git log --all` - Displayed the full commit history and branch refs