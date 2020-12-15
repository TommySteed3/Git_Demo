# Git for TEA
## TEA COMMANDS

1. git clone
2. git checkout -b dev
3. Make changes on your copy of the code.
4. git add .
5. git commit -m "message"
6. git checkout main
7. git merge dev
8. git fetch
9. git pull --rebase
10. git push

# What do these commands do?

**git clone:** This command makes a copy of selected repository.  

**git checkout -b dev:** This command actually performs 2 functions:
a. Creates a new branch called dev.
b. Checks out the new dev branch.

**Make changes on your copy of the code** For TEA projects - this means updating the R code.  You will make your coding changes on the cloned version of your code base.

**git add .** Add your changes to items ready for commit.

**git commit -m "message"** Move your changes into the repository of your active b  Thiranch (in our case - this is dev).

**git checkout main**  Checkout the main branch again - where you have not made any changes since your clone of the remote repository.

**git merge dev**  Bring the changes you made in your dev branch - into your main branch.  This is all still on our machine and does not impact our Git Hub repository.

**git fetch**  This is a pull without the merge.  Basically look to see if you have any conflicts.  Has anyone else made changes to the remote repository since you cloned, that you are unaware of?  Should not be the case.

**git pull --rebase**  This will move the changes uncovered in your fetch - into your local repository.  Your local repository will now reflect any changes made to the remote repository.  Still need to update with changes you made in your dev branch.  Also still haven't moved anything to the remote (Git Hub) repo.

**git push**  Move your changes up to your Git Hub repo.  With TEA - this means pushing up for approval by Phil Sanchez and Tommy Steed.
