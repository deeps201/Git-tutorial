# GIT-TUTORIAL
Git and Github general introduction

## GIT

Definition: Free and open source version control system


## VERSION CONTROL

Definition: Process of managing the changes in documents,computer programs, large web sites and other collections of information. It also helps to
track down bugs or go back to previous versions of the code.


## TERMS
1) DIRECTORY: Folder

2) TERMINAL OR COMMAND LINE: Interface for text commands.

3) CLI: Command Line Interface.

4) cd: Change directory.

5) CODE EDITOR: Word processor for writing code.

6) Repository: Project, or the folder/place where your project is kept.

7) GITHUB: A Website to host your repositories online.

8) GIT: Tool that tracks the changes in your code overtime.

## COMMANDS

1) CLONE: Bring a repository that is hosted somewhere like github into a folder on ypur local machine.

2) ADD: Track your file and changes in git.

3) COMMIT: Save your files in git,

4) PUSH: Upload git commits to remote repository.

5) PULL: Download changes from remote repository.

## STEPS TO CLONE

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
      
## STEPS FOR PUSH AND PULL

## 1) To generate keys
     ssh-keygen

## 2) Push command
     git push origin master

## When we create a folder locally

## STEP1:
     git init

## STEP 2:
     git status

## STEP 3: 
     git add

## STEP 4:
     git commit

## STEP 5:Create an empty repository in github
      git remote add origin(link of the empty repo)

## To display the activity
       git remote -v
       
## Upstreaming
     git push -u origin master/main

## GIT_BRANCHING
*Master branch-default branch
*Feature branch-additional branch
*Hotfix branch-bug fixing branch
