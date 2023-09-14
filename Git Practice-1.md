1. GitHub Integration
2. Git Commands
3. CodeCommit Integration
4. CodeCommit Commands


(1) GitHub Integration:
ssh-keygen -t ed25519 -C "your-email@example.com
cat ~/.ssh/id_ed25519.pub

(2) Git Config Update
git config --global user.name "Cloudtech Trainer"
git config --global user.email cloudtech.trainer@gmail.com

(3) Initalize and Push to master branch
mkdir test
cd test
git init 
git status
vi main.txt
git add .
git commit -m "message"
git push -u origin master

(4) Create new branch and push to new branch
git branch
git branch <new-branch-name>
git switch <new-branch-name>

vi feature.txt
git add .
git commit -m "message"
git push -u origin <new-branch-name>

(5) Merge changes to Master branch
git switch master
git merge origin <new-branch-name>
git add .
git commit -m "message"
git push -u origin master

(6) Pull from another branch and Push

Manually add a branch in GitHub
git switch master
git pull origin <manually-added-branch>

git add .
git commit -m "message"
git push -u origin master

(7) Revert recently changed
git log
git revert <commit-hash>
git push origin -d branch-name