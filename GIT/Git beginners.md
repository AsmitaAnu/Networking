# Git

#### What is git ?

Free and Open source Version Control System.

#### What is Version Control ?

It is basically ,the management of changes to any docuuments, computer program, large website, and other collection of information.

#### What is the difference between Git and GitHub ?

Git is the tool which track all the changes in your code overtime and Github is a website you host all of your git repositories .

## GIT Commands

* clone:- Bring a repository that is hosted somewhere like Github into a folder on your local machine. 
* add:- Track your files and changes in git.  Eg:- git add <file>
* commit:- Save ypur file in Git. 
* push:- Upload git commit to a remote repo, like github. 
* pull:- Download changes from remote repo to the loacl machine. 

#### Commands to commit the code
  
* git status
* git add <filename>
* git commit -m "<context>"
* git push origin main
  
#### How to check the branch of the git ?
  git branch
#### How to change the branch in github ?
  git checkout -b feature
  
  *checkout is used to switch the branch and to create new branch need to use -b.
  
#### git diff : This command is used to show the me all the lines that have been changed .
#### git merge : This command is used to merge to different branch.
#### git log : This command is used to show the commit msg which we had done while commiting the code.
#### git reset : This command is used to change back the commit you have done early .
#### git reset HEAD~1 : This command is used to get 
#### How to delete a branch ?
 git branch -d branchname
  
git commit -am context :- This command is basically used to add and commit both to a modifed file, which means the file should be already present and commited before.
  
#### what is PR ?
It is basically a request to have your code pulled into another branch . In the example we're using feature branch , and we want to have ouur code pulled into the master branch . so, we make a PR from the feature branch to the master branch. 
  
  
  
  
  
  
  
