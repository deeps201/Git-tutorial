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

1--> git clone (link http or ssh)

## 2--> to display the everything
         ls-la
      
## 3--> to view the status of the repo
        git status
      
## 4--> to track files
       git add (filename including extension)
   --> track all changes
       git add .
      
## 5--> to add a message and description
        git commit -m (filename) -m (description)
      
## STEPS FOR PUSH AND PULL

1--> to generate keys
     ssh-keygen

2--> push command
     git push origin master

## When we create a folder locally

1)git init

2)git status

3)git add

4)git commit

## create an empty repository in github
5)git remote add origin(link of the empty repo)

## to display the activity
       git remote -v
       
7)git push -u origin master/main
