Introduction to Git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Git web

Installation of Git
Downloads for Mac OS X, Windows, Linux and Solaris can be found on the official web of git - downloads. Instructions to install Git for Linux, Mac and Windows, using these downloads, are described on the Atlassian Documentation - Set up Git.

Setting up Git
To start using Git, it is required to create a user and a ssh-key for authentication with the remote repository.

Git Commands
Clone a repository
Clone command

git clone 
Check git-commands folder to see all the files included in the repository.

Work in branches
See what branch you are on:

git branch
Create a new branch:

git checkout -b branchname
Switch between branches:

git checkout branchname
Delete branch locally:

git branch -D branchname
Delete branch globally:

git push origin --delete branchname
Add, modify or remove files
You can create, delete and modified files on the current folder of the repository. Track these files:

git status
Add and rm files to the index:

git add filename
git rm filename
Update new, removed and modified files with any of these commands:

git add -A
git add -all
git add -no-ignore-removal
Make a commit to record changes of the repository:

git commit -m "useful message"
Pull and push
To send recorded changes to the remote repository:

git push origin branchname
To receive recorder changes from the remote repository:

git pull origin branchname
Merge branch with master repository
Update my branch according to the master:

git checkout branchname
git pull origin master
Merge my brach into master:

git checkout master
git merge brachname
To see how it was merged:

git log
Change url when repository has change name
git remote set-url origin [updated link]
Git Cheet Sheets
Basic Cheet Sheet - https://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf

Commands Sequence - http://www.cheat-sheets.org/saved-copy/git-cheat-sheet.pdf

Github end