# devsecops-tasks-prajwalmr
## Date: 2025-08-05

### 🔧 Git Configuration
git config --global user.name "PrajwalMR"
git config --global user.email "prawjalrevankar593@gmail.com"
git config --list

### 📁 Repository Setup
git clone https://github.com/Prajwalmr55/devsecops-tasks-prajwalmr.git
cd devsecops-tasks-prajwalmr
mkdir 2025-08-05
cd 2025-08-05
touch task1.txt task2.txt

### 📦 Staging and Committing
git status
git add .
git commit -m "Initial commit with two task files"

### 🔁 Making Changes
echo "This is Task 1 content" >> task1.txt
git status
git add task1.txt
git commit -m "Updated task1.txt with content"

### 🧾 Logs and Show
git log
git show <commit-id>

### 🚀 Push to GitHub
git push origin main

### 🔁 Pull Remote Changes
git pull
