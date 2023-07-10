Added as a confilcter in the remote repo

git pull
  - synchorized the local repo to the remote repositorty

git status
  - shows all files the have been modified and created that has not been commited yet or untracked by git

git add
  - add files to be committed

git commit
  - save code locally 
  - adds a description using the '-m' flag

git push |origin| [branch]
  - pushes the code to a remote repository
  - origin states what branch in your local repo to be push

git remote add origin [origin]
  - adds a reference to a remote repository

git branh
  - show the list of branch and current branch 

git branch [name]
  - adds a branch locally
  - with flag '-b' swithes to the the newly created branch


git checkout [name]
  - changes branch

git checkout -b [name] 
  - crates a branch and changes to that branch

git branch -d [name]
  - deletes a local branch

git reset [name]
  - unstage a file or all of files using

git reset HEAD@{[number]}
  - undo the commit by a number

git reset [hash]
  - undo the commit or move to a spefied commit using hash from 'git log'

git add -p [name]
  - adds a stage on a patch level (portion of code)

git merge --abort 
  - aborts a merge


NOTE:
  Perfect Commit Mesage
    - Subject: consice summary of what happened
    - Body:
        => What is different from before
        => What's the reason for the change
        => Anything to watch out for / anything particularly remarkable

  Merge Conflict
    - occurs when code is integrated from different source
