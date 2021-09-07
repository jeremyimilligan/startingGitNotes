## getting up and running
vcs (version control system)
can revert back to previous version of file

3 stages
    committed
    modified - new changes but not committed
    staged 

.get directory (repo)
    committed amd recorded
working directory
    modified

Command line
    pwd - print working directory
    cd - change directory 
    ls - list files (dir for windows)
    touch - new file
    mkdir - create new folder

git --version
git config --global user.name "name"
git config --global user.email "name@email.com"
man git (shows git commands)
git help _____ (type section)

git repository
    cd (into project folder)
    git init
    cd .git
    cd ..

echo "# filename" >> README.md
git add . (adds all files to staging area)
git commit -m "first commit"
git remot add origin _____(type in https url)
git push -u origin master

## basic commands
if you change a file after you git add, you must git add again

git diff --staged 
    -compared file versions
    -file metadata
    -change markers for file A/B
    -chunk head (which lines were changed)
    -chunk changes (- old/+new content)

git commit -a -m "input message" (commits everything in wd, and adds message)

## extended commands
git log - returns info from previous commits
git log -1 (asked for limited number of commits)
git log --oneline (all commits in one line)
git log --stat 
git log --patch

git checkout -b ______ (type name of new branch)
    this will create/put you in a new branch
    changes on new branch wont effect the main
git reset
    git reset --soft (puts reset back to staging)
    git reset --mixed (moves back to wd)
    git reset --hard (moves to trash)

git push origin master (makes master up to date with local changes)
