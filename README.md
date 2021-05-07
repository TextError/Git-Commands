# Git-Commands #

- ## General: ##
  - #### ls -la ####
    - Show all files including hiden ones

- ## Git: ##
  - #### git init ####
    - Initialize git repository
  - #### git status #### 
    - Shows all files that has been updated/created or deleted
  - #### git add . ####
    - Select all the files, and move them to the staging area
  - #### git commit -m "message" ####
    - Commits your file(s) with your message
  - #### git commit -am "message"
    - Adds and Commit your file(s) with your message
    - Works for modified file(s) only
  - #### git remote add origin `https://GithubLink` ####
    -  Links your project to your Gitgub repository
  - #### git push -u origin master ####
    - Push the file(s) to Github -u default
  - #### git push ####
    - Push the file(s) to Github
  - #### git pull ####
    - Pulls and updates your code from Gitgub

- ## Branching ##
  - #### git branch ####
    - Show branches
  - #### git checkout -b `name-of-new-branch`
      - Creates new branch
  - #### git checkout `name-of-branch`
    - Switch to designated branch

- ### Master Branch ###
  - git diff 'name-of-branch'
    -  Shows files that has been changed
  - git merge 'name-of-branch'
    -  Merge feature branch to Master
  - git branch -d 'name-of-branch'
    - Deletes the branch

- ### Feature Branch ###
  - git push -u origin 'name-of-branch'
    - Push changes to the named branch