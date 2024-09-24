git --version
git config --global user.name "Tanmoy023"
git config --global user.email "tanmoypatra369@gmail.com"
git config --list

git clone https://github.com/Tanmoy023/DemoRepo.git
cd .\DemoRepo\
git status

git add . 
git commit -m "changed massage"
git push origin main    // uplad our all changes form local repo to remote repo

cd ..   // come back to previous directory
mkdir localRepo     // create a new directory named localRepo
gin init    // init is used to Initialized empty Git repository