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
Created a new local directory and initialized Git:

```bash
mkdir devops-project
cd devops-project
git init
✅ 2. Create GitHub Repository & Link to Local Repo
Created a remote repo on GitHub and linked it:

bash
Copy
Edit
git remote add origin https://github.com/Yash5103/devops-project.git
✅ 3. Configure Git Identity
Configured user name and email for Git commits:

bash
Copy
Edit
git config --global user.name "Yash Kachale"
git config --global user.email "your-email@example.com"
✅ 4. Create and Push main Branch
Created initial commit and pushed the main branch:

bash
Copy
Edit
touch README.md
echo "# DevOps Version-Controlled Project" > README.md
git add .
git commit -m "Initial Project Setup"
git branch -M main
git push -u origin main
✅ 5. Create .gitignore File
Ignored unnecessary files:

bash
Copy
Edit
touch .gitignore
echo "node_modules/" >> .gitignore
echo ".env" >> .gitignore
✅ 6. Create & Push dev Branch
bash
Copy
Edit
git checkout -b dev
git push -u origin dev
✅ 7. Create & Push feature Branch
Made a new feature branch and pushed it:

bash
Copy
Edit
git checkout -b feature
# Edit or add any files
git add .
git commit -m "Added feature section in README"
git push -u origin feature
✅ 8. Create Pull Request & Merge
Opened a Pull Request from feature → dev

Reviewed and merged using GitHub interface

Deleted feature branch after merge

✅ 9. Tagging a Release Version
bash
Copy
Edit
git tag -a v1.0 -m "First stable version"
git push origin v1.0
✅ 10. Markdown Documentation
This README.md file includes clear documentation for all the tasks performed in this project.

🌳 Branching Workflow Summary
main: Stable, production-ready code

dev: Active development branch

feature: Temporary feature implementation branches

📝 Conclusion
This project demonstrates version control workflows using Git and GitHub with real-world DevOps branching strategies, PRs, tags, and documentation.

👨‍💻 Author
Yash Kachale

yaml
Copy
Edit
