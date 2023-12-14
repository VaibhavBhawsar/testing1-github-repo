# testing-github-repo
Testing Github Repo | DevOps Session 1: Git & Github

Git
// Checking Version
git --version
// Clear Screen
clear
// Clone Repo
git clone https://github.com/atulkamble/testing-github-repo.git
// List Files and folders
ls
// Check Path
pwd
// Navigate to local directory
cd .\testing-github-repo\
ls
// Create new file | Windows >> Linux touch new.py
New-Item new.py
ls
git status
git add new.py
git status
git push -o origin main
// Configure user and email
git config --global user.name "Full Name"
git config --global user.email "Email id"
// Push Code
git push origin main
git commit -m "Added New Python File"
git push origin main
code new.py
git commit -m "Added Code to File"
git add new.py
git status
git commit -m "Modified Code"
git push origin main
