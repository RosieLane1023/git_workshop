key git commands learnt so far:

git diff - finds differences in files between current working and last commit. 
git status - status of my directory. Lists all uncommitted changes. 
git add �filename_to_add    adds file s next commit
git commit -a     commits all added files and lets you write a comment. 
git log -n 2    gives a log of all the changes/ commits that have taken place. -n 2 only shows most recent 2 changes. 
git checkout master    goes back to the master version. 
git checkout version_string     can check out old versions
git checkout version_string filename    restores an old file
git checkout -b branch_name    start a new branch from whichever file your head is currently in. 
git branch        tells you branch info - what branch you are on, and which others exist.
git checkout new_branch    can also use this to move head between branches
git mv something.md background.md    moves or renames something to background

git push   pushes your changes from your computer into the cloud
git pull   pulls changes from the cloud onto your computer

useful to know:
.git directory will be corrupted and break if used with another version of git. 
