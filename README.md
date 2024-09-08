# git

Git repository: data objects and references. Git keeps track of files, but not folders. Git doesn't keep track of empty folders.

Git command

git clone

git init: creates a new git repo, with data stored in .git directory

git status

git add <filename>

git add . : add all changes

git commit -m <message>: creates a new commit with message exactly explain what change

git log --all --graph --decorate [--oneline]: --decorate flag shows all the references(branches, tags..) that points to each commit.

git log -p: all changes are shown in the history

git diff <filename>: show differences to last commit

git diff --staged <filename>: show diff even in staging area

git mv: rename a file in Git

git restore . : remove all changes made
 
git restore --staged <filename>: bring the file back to working directory

git checkout : look back at a specific commit

git branch: shows branches

git branch <name>: cerates a branch

git checkout -b <name>: creates a branch and switches to it

git push 

git pull

