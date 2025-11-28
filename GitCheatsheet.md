git init > creates a new Git repository

git status > inspects the contents of the working directory and staging area

git add > adds files from the working directory to the staging area

git diff > shows the difference between the working directory and the staging area

git commit > permanently stores file changes from the staging area in the repository

git log > shows a list of all previous commits

git show HEAD > show last Commit

git checkout HEAD FILENAME > discard changes

git reset commit_SHA > resets to previous commit

git reset HEAD filename > unstages files in staging area

git stash > stashes work (if you want to change branches to do something else, saves in local directory)

git stash pop > get back the saved stash

git branch -a > shows all branches

git branch BRANCHNAME > change branch

git log --oneline > shows the list of commits in one line format.

git log -S "keyword" > search for specific commit

git log --oneline --graph > get visual representation of which 

git commit --amend --no-edit > edit your previous commit without renaming it (if you made a little mistake)


## Set Up Git Locally

>git config --global user.name "NAME"
>
>git config --global user.name
>
>git config --global user.email "YOUR_EMAIL"

## Linking with GitHub

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kabusch940/git_practice.git
git push -u origin main

git pull --rebase origin main >> if it does not work

