# cookrepo
# cookrepo

GIT Notes

ADDING FILES FOR TRACKING PRIOR TO COMMIT
git add <filename>

adding -a to commit adds all files

COMMITING CHANGES
git commit -m "describe changes here"
OR IF YOU NEED TO ADD FILES
git commit -a -m "describe changes here"

PUSHING CHANGES TO BRANCH
git push origin master
OR IF ON A BRANCH
git push origin testbranch

HOW TO MERGE TO MASTER
git checkout master (switch to master)
git merge test
git push origin master (to push merge branch)


CREATING A BRANCH
git checkout -b testbranch 

CHANGING BETWEEN BRANCHES
git checkout master

DELETING A BRANCH (locally)
git branch -D testbranch

DELETING REMOTE BRANCH
git push origin --delete testbranch

ADDING REMOTE GIT REPO
git remote add git@github.com:nsyed1/reponame.git
(note sure about this one)

CHECKING REMOTE REPO
git remote -v

CHECK WHICH BRANCH YOU'RE ON
git branch
git status


configuring after GIT install
git config --global user.name "username"
git config --global user.email "your@email.com"

INITIALIZING FOLDER FOR GIT
git init
