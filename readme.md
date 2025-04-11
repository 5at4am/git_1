# starting 

### setup git/github account in vs code 
- 1. open vs code
- 2. open terminal in vs code
- 3. run command: git config --global user.name "yourgithubusername"
- 4. run command: git config --global user.email "yourgithubemail"
- 5. run command: git add .
- 6. run command: git commit -m "your commit message"
- 7. run command: git branch -M main
- 8. run command: git remote add origin https://github.com/yourgithubusername/
- 9. run command: git push -u origin main

## beginner level command
- git init                  // initialize a new git repository
- git add .                 // stage all files in the current directory
- git commit -m "first commit" // commit the staged files with a meaningful message
- git status // check the status of your repository
- git log // view the commit history
- git branch -M main        // rename the default branch to main
- git remote add origin https://github.com/username/repository.git // link your local repository to the remote repository on GitHub
- git push -u origin main // push to remote repository for the first time
- git pull origin main // pull the latest changes from the remote repository

## intermediate level command

- git branch -a             // list all local and remote branches
- git checkout main // to switch to main branch
- git branch -d feature/new-feature // to delete a branch
- git merge feature/new-feature // to merge a branch into main
- git tag -a v1.0 -m "version 1.0" // to create a new tag 
- git push origin --tags // to push the tags to the remote repository
- git cherry-pick <commit_hash> // to apply the changes from a specific commit to the current branch
- git revert <commit_hash> // to undo the changes from a specific commit
- git reset --soft HEAD~1 // to undo the last commit and keep the changes in the staging area
- git reset --hard HEAD~1 // to undo the last commit and discard the changes in the staging area
- git stash // to save the changes in the staging area and discard them
- git stash pop // to apply the changes saved in the stash
- git stash drop // to discard the changes saved in the stash


## advance level command

- git rebase -i HEAD~5 // to interactively rebase the last 5 commits
- git rebase -i <commit_hash> // to interactively rebase from a specific commit
- git rebase --onto <new_base> <old_base> // to rebase a branch
- git merge --no-ff <branch_name> // to merge a branch without fast-forwarding
- git merge --squash <branch_name> // to merge a branch without creating a new commit
- git merge -X theirs <branch_name> // to merge a branch with the "theirs