git switch main ---- switchin branch to main
git checkout -b feature/profile -- to make branch name feature/profile
git branch --- show all branches
git merge feature/profile --- merging branch to main
git pull -- pulling latest code 
git diff main feature/profile --- showing up the differences btw main and feature/profile by +-

git diff-- shows changes in the working directory that haven't been staged yet.
git diff --staged --- after GIT ADD the file---it shows exactly what will be committed.

git remote -- shows the remotes (origin)
git remote add backup git@github: --- add remote named(backup)
git remote remove backup --- delete the remote(backup)