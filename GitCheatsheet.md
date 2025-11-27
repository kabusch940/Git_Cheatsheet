git init creates a new Git repository
git status inspects the contents of the working directory and staging area
git add adds files from the working directory to the staging area
git diff shows the difference between the working directory and the staging area
git commit permanently stores file changes from the staging area in the repository
git log shows a list of all previous commits

git show HEAD > show last Commit

git checkout HEAD FILENAME > discard changes

git reset commit_SHA > resets to previous commit

git reset HEAD filename > unstages files in staging area

git stash > stashes work (if you want to change branches to do something else, saves in local directory)

git stash pop > get back the saved stash