#Open the ppt first, these are just a few liners for what to do in the ppt

What is a VCS?
A version control system is a software to manage a project by having all the different versions of your files saved
Some examples are git, mercurial (hg), subversion (svn)

What is git?
git is a VCS developed by Linus Torvalds for the development of the Linux Kernel, in 2005

What is a repository?
Basically another name for a project
A repository can have as many files/folders as you want
All git data is stored in repositories

git commands - 
git config -- setting name and email
git init -- initializing a repository
make some files, add only some
git status (showing files unstaged, staged)
git diff (, git diff --cached)
What is a commit?
Basically like a save
Can also consider it a snapshot of various states in your git repository
Can by identified by its unique hash

Make a commit
Browse directory at previous commit
Git status at bash

git commit (Explain -a, -m flags)
(Create a few commits to get a small log to work on)
git log (Show some flags like --author, --committer, --oneline)
git show (git show to show current HEAD, git show <sha> to show a certain commit)
git revert
git reset
git checkout

Tell them about services like github, gitlab, etc.
Then make sure everyone has a github account, and show them how to create a repository and push
Then show them how they can view the log in the commits tab, check what a commit changed, etc.
How to edit and commit files online directly.
How to clone a repository from github or pull into an existing local repository

ksdfg:
make a repo online
what a remote is
  Basically another name for a project
  A repository can have multiple files
push repo on hub
add files, upload files
commit history, browse files at previous commit
pull repo onto bash
go to hub, make a branch, make some change
pull repo first, show no branch in git branch, then pull branch
go to github, start a pull request from branch
clone - bash guys: revert commit
fork me and make a pull request
