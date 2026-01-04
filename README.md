# This is my local Repository

# The Basic workflow of github is below

✅ BASIC GIT & GITHUB WORKFLOW (FINAL)
🔹 ONE-TIME SETUP (only once per system)
git config --global user.name "Your Name"
git config --global user.email "youremail@gmail.com"

🔹 CASE 1: STARTING A NEW PROJECT (Local → GitHub)
1️⃣ Create project & initialize Git
git init

2️⃣ Create / edit files
index.html
style.css
README.md

3️⃣ Check status
git status

4️⃣ Stage files
git add .

5️⃣ First commit (VERY IMPORTANT)
git commit -m "Initial commit"

6️⃣ Rename branch to main (recommended)
git branch -m main

7️⃣ Connect GitHub repo
git remote add origin https://github.com/USERNAME/REPO.git

8️⃣ Push to GitHub
git push -u origin main

🔹 CASE 2: WORKING ON AN EXISTING GITHUB REPO (Clone → Edit → Push)
1️⃣ Clone repository
git clone https://github.com/USERNAME/REPO.git
cd REPO

2️⃣ Check branch & status
git branch
git status

3️⃣ Make changes (example: README.md)
Added new project description

4️⃣ Check changes
git status

5️⃣ Stage changes
git add README.md

6️⃣ Commit
git commit -m "Update README"

7️⃣ Push
git push

🔹 DAILY DEVELOPER WORKFLOW (MOST USED)
git status
git add .
git commit -m "Meaningful message"
git push

🔹 IMPORTANT COMMANDS (MUST REMEMBER)
Command	Purpose
git status	Check changes
git add	Stage files
git commit	Save locally
git push	Upload to GitHub
git pull	Download updates
git branch	Show branch
git checkout	Switch branch
🔹 COMMON ERRORS & FIXES
Error	Fix
nothing to commit	No file change
src refspec main	No commit yet
rejected push	git pull --rebase
working tree clean	Everything pushed