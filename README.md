# 🔥 Essential Git Commands for Real-World Projects

This repository is created to practice and understand **essential Git & GitHub commands** used in real-world software development projects.

It is ideal for:
- Students
- New developers
- Anyone revising Git basics through hands-on practice

---

## 🚀 Topics Covered

- Initializing a Git repository
- Pushing code to GitHub
- Cloning repositories
- Working with branches
- Merging branches
- Fetch vs Pull
- Undoing commits and restoring files

---

## 🛠️ How to Push a Local Repository to GitHub

### Create a Repository on GitHub  
Create a new empty repository on GitHub (no README).

### Open Git Bash and Navigate to Your Project
```bash
git init
git status
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/your-username/MyProject.git
git branch -M main
git push -u origin main

⚠️ If you get an error while pushing

git pull origin main --allow-unrelated-histories

📥 Clone a Repository

Navigate to your desired local directory:

git clone https://github.com/your-username/Practice-GIT-Commands.git
cd Practice-GIT-Commands
git status

🌱 Working with Branches

Create a branch:

git branch feature-header
git checkout feature-header

OR (create and switch in one command):

git checkout -b feature-header

🔀 Merge to Main Branch

git checkout main
git merge feature-header

🧹 Delete a Branch

git branch -d feature-header

🔄 Fetch vs Pull

git fetch   # Download updates without changing files
git pull    # Fetch and merge updates into local files

⏪ Undo & Restore

git reset --soft HEAD~1   # Undo commit, keep changes staged
git reset --hard HEAD~1   # Undo commit and delete changes
git checkout -- <file>    # Restore a specific file

💡 Practice Challenge

Create a GitHub repository

Clone it locally

Create a new branch

Make a small change

Commit the change

Merge it into main

Push everything to GitHub

✅ If you completed all steps, you’ve successfully practiced basic Git commands!

📝 Note

All repository names, branch names, and URLs used here are examples only.
Replace them with your own project details when practicing.

📌 Author

Sandeepa Chathumina
Software Engineering Undergraduate

⭐ If this repository helped you, feel free to star it!
