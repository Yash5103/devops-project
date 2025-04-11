# 🚀 DevOps Version-Controlled Project

## 📌 Objective
The goal of this project is to learn and implement Git best practices for managing a DevOps project with proper version control workflows.

---

## 🛠️ Tools Used
- Git
- GitHub
- Markdown

---

## 📁 Project Structure

devops-project/ ├── README.md ├── .gitignore └── (other project files)

yaml
Copy
Edit

---

## 📖 Tasks Performed

### ✅ 1. Initialize Git Repository
- Created a new directory: `devops-project`
- Ran `git init` to initialize a local Git repository

```bash
mkdir devops-project
cd devops-project
git init
✅ 2. Create GitHub Repository & Link to Local Repo
Created a remote repo on GitHub named devops-project

Added remote origin to local repo

bash
Copy
Edit
git remote add origin https://github.com/Yash5103/devops-project.git
✅ 3. Configure Git Identity
Set global user name and email to associate with commits:

bash
Copy
Edit
git config --global user.name "Yash Kachale"
git config --global user.email "your-email@example.com"
✅ 4. Create and Push main Branch
Created initial commit

Created and pushed main branch to GitHub

bash
Copy
Edit
touch README.md
echo "# DevOps Version-Controlled Project" > README.md
git add .
git commit -m "Initial Project Setup"
git branch -M main
git push -u origin main
✅ 5. Create a .gitignore File
Added files/folders to ignore in Git tracking (e.g., node_modules, .env, etc.)

bash
Copy
Edit
touch .gitignore
echo "node_modules/" >> .gitignore
echo ".env" >> .gitignore
✅ 6. Create & Work in dev Branch
Created a dev branch and pushed it to GitHub.

bash
Copy
Edit
git checkout -b dev
git push -u origin dev
✅ 7. Create & Work in feature Branch
Created feature branch from dev

Made a small change (e.g., updated README.md)

Committed and pushed to GitHub

bash
Copy
Edit
git checkout -b feature
# Edited README.md or added new files
git add .
git commit -m "Added feature section in README"
git push -u origin feature
✅ 8. Create Pull Request & Merge
Created a pull request on GitHub from feature to dev

Merged using GitHub UI

Deleted the feature branch after successful merge

✅ 9. Tagging
Created a tag to mark version milestone

bash
Copy
Edit
git tag -a v1.0 -m "First stable version"
git push origin v1.0
✅ 10. Markdown Documentation
All steps were documented using README.md

Clear step-by-step guide for new contributors to understand project flow

🌳 Branch Workflow Summary
main: Stable production-ready branch

dev: Integration branch for tested features

feature: Temporary branches to develop new features

📝 Conclusion
This project demonstrates an organized Git-based DevOps workflow using branching strategies, pull requests, tags, and markdown documentation to enable easy collaboration and version tracking.

👨‍💻 Author
Yash Kachale
