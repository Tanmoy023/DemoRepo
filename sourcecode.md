git --version
git config --global user.name "Tanmoy023"
git config --global user.email "tanmoypatra369@gmail.com"
git config --list

git clone https://github.com/Tanmoy023/DemoRepo.git
cd .\DemoRepo\
git status

git remote add origin https://github.com/Tanmoy023/localRepo.git
git remote -v   // to verify to the remote repo
git branch //  to check the branch
git branch -m main // to change the branch name
git checkout -b newBranch1     // to create a new breanch which name is newBranch1
git branch -d newBranch1    // to delete the branch
git checkout main   // to change the branch in to main
git add . 
git commit -m "changed massage"
git push origin main    // uplad our all changes form local repo to remote repo

cd ..   // come back to previous directory
mkdir localRepo     // create a new directory named localRepo
gin init    // init is used to Initialized empty Git repository

git remote add origin https://github.com/Tanmoy023/localRepo.git
git branch -M main
git push -u origin main

git diff main   // check the difference between working branch with main
git merge main  // to merge the working branch with main

git reset fileName  // to reset our changes respected to given fileName (when we add only)
git reset   // to reset all filed (when we add only)

git reset HEAD~1    // to reset our reset commit
git log     // to check our all 
git reset commitHash // to reset upto a perticular commit