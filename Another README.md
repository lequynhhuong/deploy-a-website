**Some commands for Git**

`git init` create a new repo

`git status` inspects the new content of the working directory and staging area

`git add` add files from working directory and the staging area. more than 2 filenames can be added with a space 

`git diff` show the differences between the working directory and the staging area

`git commit` permanently stores file changes from the staging area in the repo

`git log` show all list of all commits

`git show HEAD` the output of this command will display everything the git log command display for the HEAD commit, plus all the changes that were committed 

`git checkout HEAD filename` discards changes in the working directory 

`git reset HEAD filename` unstages file changes to in the staging area. 

`git reset 'first 7 number of the commit'` to reset previous file

`git branch` to check which branch one is on

`git branch new_branch_name` to create a new branch name

`git checkout branch_name` to switch to a new branch

`git merge branch_name` to merge branch name to the master

`git branch -d branch_name` too delete the branch specifies

`git clone` creates a local copy of a remote

`git remove -v` lists a git project's removes 

`git fetch` fetch works from the remote into the local copy

`git merge origin/master` merges origin, master into your branch

`git push origin <branch_name>` pushes a local branch to the `origin` remote 