# starting 

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
- git cherry-pick <commit_hash> // to apply the changes from a specific commit to th
