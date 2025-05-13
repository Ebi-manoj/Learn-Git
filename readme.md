# LEARN GIT BASICS

### Some Basic Linux Commands

- **mkdir** _<-folder name>_ : Create a new Folder
- **cd** _<-folder name>_: Change directory
- **ls** : List all your folder in the directory
- **ls -a** : List all hidden folder in the directory
- **touch** _<-filename>_ : Create a new file
- **vim or nano** _<-filename>_ : Editor for editing the file
- **cat** _<-filename>_ : Show all the contents in file
- **rm -rf** _<-filename>_: Remove the file

### Basic Git Commands

- **git init** : This will initialize the git in your directory
- **git status** : This will list all the changes that are not in the history of your project(untracked changes)
- **git add** : Add files to stage that are untracked(all the modified files)
- **git commit -m ""** : Commit staged changes with a message.
- **git reset _commit_** : Reset to given commit all commit above will be unstaged
- **git restore** _<-filename>_: Restore all the changes made till the last commit in the specified file
- **git log** : Log all the commit you have done
- **git stash** : This is like you made changes and you dont want to commit but you need to revert those changes also keep the modified changes and apply those changes whenever you need(using git stash pop)
- **git stash pop** : This will pop out the stashed changes
- **git stash clear** : Command to clear the stashed changes, all the stashes will be empty
- **git branch** : This will list all the branch you created
- **git branch** _name_: Create a new branch
- **git checkout branchName** : Switch between branches
- **git clone _repo-link_** : Clone repository to your local
- **git rebase** : To merge commits by pick and squash

