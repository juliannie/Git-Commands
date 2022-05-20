# Git CheatSheet

This is a git cheatsheet containing the basic Git workflows.

## Git Commands

clone --> Bring a hosted repo to your local machine

add --> track files and changes in Git

commit --> Save your files in Git

push --> Upload Git commits to a remote repo

pull --> Download changes from remote repo to local machine (opposite of push)

## Clone repo from Github

git clone <SSH address> --> run this in the directory you want to clone the repo to
  
ls -la --> shows all files, including hidden --> verify that .git folder exists
  
## Add a new local Repo to Github

git init --> initialize Git repo

git status --> check untracked or changed files

git add <filename> or git add . (all files) --> add files for commit
  
git commit -m <message> -m <description> --> commit changes of tracked files locally
  
To push new local file, go to github and create new empty repo with name <newRepo> and copy SSH adress <SSH address>

git remote add origin "<SSH address>" --> create connection between local and github repo (only necessary once)

git remote -v --> check all remote repositories connected to this repo
  
git push origin master --> pushes local to github (use git push -u origin master to set origin master as default, later use git push to push to default branch)
  

