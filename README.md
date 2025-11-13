🧠 Git & GitHub Practice
📅 Date

13 November 2025

📘 Overview

Today, I learned how to use Git and GitHub effectively. I practiced creating repositories, committing changes, pushing and pulling updates, creating pull requests, and resolving merge conflicts. This helped me understand how collaboration works in real-time on GitHub.

🔧 Git Commands Practiced
🏗️ 1. Setup and Configuration
git config --global user.name "YourName"
git config --global user.email "your-email@example.com"


To verify configuration:

git config --list

📂 2. Initialize Repository
git init


This command creates a new Git repository in your current folder.

➕ 3. Add Files to Staging Area
git add filename


or to add all files:

git add .

💬 4. Commit Changes
git commit -m "Your commit message"

🌐 5. Link Local Repository with GitHub
git remote add origin https://github.com/YourUsername/YourRepository.git


Check if remote is added:

git remote -v

🚀 6. Push Changes to GitHub
git push -u origin main


For future pushes:

git push

📥 7. Pull Latest Changes from GitHub
git pull origin main

🔄 8. Clone a Repository
git clone https://github.com/Username/Repository.git

🌿 9. Create and Switch Branches
git branch branch-name
git checkout branch-name


Or create and switch together:

git checkout -b new-branch

🔀 10. Merge Branches

First, switch to main:

git checkout main


Then merge:

git merge branch-name

⚔️ 11. Resolve Merge Conflicts

If conflicts occur:

Open the conflicted files.

Edit manually to keep the correct code.

Stage the resolved files:

git add filename


Commit the merge:

git commit -m "Resolved merge conflicts"

💬 12. Create a Pull Request (on GitHub)

Go to your repository on GitHub.

Click “Compare & Pull Request”.

Add a title and description.

Click “Create Pull Request”.

Once reviewed, click “Merge Pull Request” and confirm.

🧹 13. Check Status and Logs
git status


To see commit history:

git log

✅ Summary of What I Learned

How to initialize and link repositories

How to commit and push changes to GitHub

How to create and merge pull requests

How to resolve merge conflicts manually

How to collaborate using branches

📽️ Demonstration

A short demonstration video is available on my LinkedIn profile:
👉 Monisha Appavu on LinkedIn
