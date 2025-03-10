# git-homework
echo "# Git Homework" > README.md
echo "This is my first Git repository for homework." >> README.md
git config --global user.name "Alisha"
git config --global user.email alisagrg102@gmail.com
cd ~/Projects
mkdir git-homework
cd git-homework
git init
touch README.md
echo "# Git Homework" > README.md
echo "This is my first Git repository for homework." >> README.md
git status
git add README.md
git commit -m "Initial commit: Added README file"
git branch -M main
git push -u origin main
