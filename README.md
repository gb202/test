git config --global user.name "gb202"
git config --global user.email "gayatribhise20@gmail.com"
mkdir makes a new directory.

cd changes the current working directory.

Now that we are in the correct directory. We can start by initializing Git!
git init 

Initialized empty Git repository in /Users/user/myproject/.git/

git status

Git Staging Environment
One of the core functions of Git is the concepts of the Staging Environment, and the Commit.
As you are working, you may be adding, editing and removing files. But whenever you hit a milestone or finish a part of the work, you should add the files to a Staging Environment.

Staged files are files that are ready to be committed to the repository you are working on. You will learn more about commit shortly.

For now, we are done working with index.html. So we can add it to the Staging Environment:

git add demo.txt
git status
git add --all
git commit -m 

Note: Short status flags are:

?? - Untracked files
A - Files added to stage
M - Modified files
D - Deleted files

git log












