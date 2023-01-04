# GIT-TUTORIAL
Git and Github general introduction

# GIT

Definition: Free and open source version control system


# VERSION CONTROL

Definition: Process of managing the changes in documents,computer programs, large web sites and other collections of information. It also helps to
track down bugs or go back to previous versions of the code.


# TERMS
1) DIRECTORY: Folder

2) TERMINAL OR COMMAND LINE: Interface for text commands.

3) CLI: Command Line Interface.

4) cd: Change directory.

5) CODE EDITOR: Word processor for writing code.

6) Repository: Project, or the folder/place where your project is kept.

7) GITHUB: A Website to host your repositories online.

8) GIT: Tool that tracks the changes in your code overtime.

# COMMANDS

1) CLONE: Bring a repository that is hosted somewhere like github into a folder on ypur local machine.

2) ADD: Track your file and changes in git.

3) COMMIT: Save your files in git,

4) PUSH: Upload git commits to remote repository.

5) PULL: Download changes from remote repository.

# STEPS TO CLONE

## 1) Git cloning
       git clone (link http or ssh)

## 2) To display the everything
         ls-la
      
## 3) To view the status of the repo
        git status
      
## 4) To track files
       git add (filename including extension)
       
## Track all changes
       git add .
      
## 5) To add a message and description
        git commit -m (filename) -m (description)
      
# STEPS FOR PUSH AND PULL

## 1) To generate keys
     ssh-keygen

## 2) Push command
     git push origin master

## To create a folder locally

     git init
     git status
     git add
     git commit

## Create an empty repository in github
      git remote add origin(link of the empty repo)

## To display the activity
       git remote -v
       
## Upstreaming
     git push -u origin master/main

# GIT_BRANCHING

1)Master branch-default branch
 ..* Creating the clone of master branch as "feature branch"

2)Feature branch-additional branch
  ..* When we make changes in the master branch it does affect the feature branch similarly for master branch.

 3)Hotfix branch-bug fixing branch

# Steps for branching

## 1)  Command to indicate current branch 
        git branch
     
## 2)  Checkout used to switch between branches 
       it checkout -b branchname 
  
## 3)  Add to git repo
       git add
       git commit -m (filename) -m (description)
       git push origin master
## 4) Combing the step of adding and committing
       git commit -am
       
       
# MERGING BRANCHES

## To find the difference between branches
     git diff branchname
## To find the status of the file
     git status
## Push the changes into the repo
     git -u origin branchname
     
# STEPS TO DELETE A FEATURE BRANCH AFTER MERGING
      git branch
      git branch -d branchname
 
 # STEPS TO UNDO A GIT 
       git reset filename(to remove commit)
       git reset HEAD ~1[^1].
       
 [^1]:HEAD- POINTER TO LAST COMMIT.
