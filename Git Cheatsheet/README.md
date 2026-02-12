# 📋 Git Command Reference

### 1. 🏁 Starting Point
*   `git init`: Initialize a new local Git repository in your current folder.
*   `git clone <url>`: Download an existing repository from GitHub to your computer.
*   `git remote add origin <url>`: Link your local folder to a specific GitHub repository.

### 2. 🔄 The "Daily Loop"
*   `git status`: **(Essential)** Check which files are modified, deleted, or ready to be saved.
*   `git add .`: Stage all your changes to prepare them for a commit.
*   `git commit -m "message"`: Save a snapshot of your staged changes with a description.
*   `git push`: Send your local commits up to your GitHub repository.
*   `git pull`: Download and merge any changes from GitHub into your local PC.

### 3. 🌿 Branching & Merging
*   `git branch`: List all branches in your project (your current one is highlighted).
*   `git checkout -b <name>`: Create a new branch and switch to it immediately.
*   `git checkout <name>`: Switch back to an existing branch (e.g., `git checkout main`).
*   `git merge <name>`: Combine the work from a side branch into your current branch.

### 4. 🕰️ Time Travel & History
*   `git log --oneline --graph`: View a beautiful, simplified map of your commit history.
*   `git diff`: See exactly which lines of text you changed since your last save.
*   `git restore <file>`: Discard changes in a specific file and go back to the last commit.

### 5. 🛠️ Advanced Syncing
*   `git fetch`: Check GitHub for updates without automatically merging them into your code.
*   `git remote -v`: List the "Remote" servers (GitHub URLs) connected to your project.
