# Lesson plan 

1. Why branches?

2. The 3 types of branches:
   - the local non-tracking branches
   - the local tracking branches
   - the remote tracking branches

3. Push/Pull branches to github

4. Create a merge conflict and show how to solve it (use vscode to select which changes to keep).

5. Do an exercise (to basically repeat what was showed before with the slides and all):
   1. create repo `class_example`, both locally and on github
   2. in master, create file `fruits.txt`, add the names of 3 fruits, one per line, Commit your changes.
   3. push `master` to github
   4. from `master`, create branch `feature/fruits`, modify the name of the second fruit and add two new fruits at the end of the file (one per line) 
   5. on github, on branch `master`, change the name of the second fruit in the file `fruits.txt`
   6. update your local branch `feature/fruits` with the contents of `master`
   7. push `feature/fruits` to github
   8. create pull request to merge `feature/fruits` into `master`
   

6. Git diff and git stash:
   1. show the git diff when we make changes in current feature 
   2. explain git stash
   3. show git diff (when there are no differences) 
   4. explain git stash list and then git stash apply 
   5. explain difference between git stash apply and git stash pop  
   6. show some more options like git diff --stat

7. How to "remove" commits
   - git reset soft vs. hard
   - git revert
   - git cherry-pick

8. Exercise to create commit use reset soft, and then create another commit use reset hard.

9. Show git checkout to a specific commit.

10. Random things that should be mentioned throughout the class:
    - git checkout -- <file> / git restore <file> (only works in git 2.23+)
    - git reset HEAD <file> / git restore --staged <file> (only works in git 2.23+)
    - git rm --cached
    - git commit --amend
    - show how to check that local branch is up to date with origin (with git log)