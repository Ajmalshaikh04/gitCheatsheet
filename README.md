# Git & Github - The Full Course

A fast-paced course for getting up to speed with Git and Github

## GIT BASICS

**git init**
<**directory**>
--
Create empty Git repo in specified directory.Run with no
arguments to initialize the current directory asagit repository.

## **git clone <**repo**>**

Clone repo located at "repo" onto local machine.Original repo can be
located on the local filesystem or onaremote machine via HTTP or SSH.

**git config**
user.name "name"
--
Define author name to be used for all commits in current repo.Devs
commonly use --global flag to set config options for current user.

git add
"directory"
Stage all changes in "directory" for the next commit.
Replace "directory" with a "file" to changeaspecific file.

git commit -m
"message"
Commit the staged snapshot,but instead of launching
atext editor,use "message" as the commit message.

git status
List which files are staged,unstaged,and untracked.

git log
Display the entire commit history using the default format.
For customization see additional options.

git diff
Show unstaged changes between your index and
working directory.
