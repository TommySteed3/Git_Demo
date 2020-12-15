# Git for TEA
Use the following commands to submit your changes for approval to
move into production.

1. git clone
2. git checkout -b dev
3. git add -all
4. git commit -m "message"
5. git fetch origin
6. git rebase origin/master
7. git checkout master
8. git pull
9. git rebase dev
10. git push -u origin master
11. git branch -D dev
12. git checkout -b dev


What do these commands do?

**git clone:** This command makes a copy of selected repository.  

**git checkout -b dev:** This command actually performs 2 functions:
a. Creates a new branch called dev.
b. Checks out the new dev branch.
