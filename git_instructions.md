# Git instruction


## What is Git?
---

Git is one of the many ways to realize version control systems. This is the most famous project in the world. There are local and internet services.


## Repository preparing
---

To prepare repository, open a folder for repository and go to command "git init"(the folder will be inicialized. Now there is one more folder with name ".git"). All right, you have repository.


## Switch between commits
---

We can make lot of branch. Then we can go to new branch ahd format documets into the branch and save new data into the branch (the new data will be invisible in other branches). But next time we can merge some branches in one branch (read head Merge).
### add commit:
- First add file to git ("git add 'file name'")
- Then type command: "git commit -m 'message'"
### checkout to commit:
- To go to some point of commit set the commands:
    - Type "git log" command to see hash names of commits
    - Type "git checkout 'five first symbols of commit hash name'"


## Git log
---

The command "git log" show all of your commits. Also the command has some parametrs:
    - "--oneline" - to see short list of commits
    - "--graph" to see commit's tree


## Branches
---

We can create some branches to have some ways to working. So we have protection "master" branch from mistakes on other branches.
    Important info:
    Before switch to some branches  you everywere need to save your data on current branch. Or you have a risk loose data from next branch, were you will go.


## Merge
---

To merge two branch in one, use command "git merge 'other branch name'". The commad add data from other branch to current branch.


## Delete branch
---

Use "git branch -D 'name branch'" to delete the branch.
