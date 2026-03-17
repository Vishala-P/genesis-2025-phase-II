Git Exercises

1. Saving Your Work

Command used: git init
Command used: touch bug.txt
Command used: nano bug.txt
Command used: git add .
Command used: git commit -m "Initial commit"
Command used: nano bug.txt
Command used: git stash
Command used: nano bug.txt
Command used: git add bug.txt
Command used: git commit -m "Fixed bug"
Command used: git stash pop
Command used: nano bug.txt
Command used: git add bug.txt
Command used: git commit -m "Finished work"
Result: Used git stash to temporarily save work, fixed a bug, restored changes, and completed the task successfully

2. Merge Conflict

Command used: git merge branch-name
Command used: git status
Command used: nano file.txt
Command used: git add .
Command used: git commit -m "Resolved merge conflict"
Result: Learned how to resolve merge conflicts manually by editing conflicting files and completing the merge.

3. Commit One File

Command used: git add file.txt
Command used: git commit -m "Committed single file"
Result: Learned how to commit only a specific file instead of all changes.

4. Commit One File Staged

Command used: git add file.txt
Command used: git commit -m "Committed staged file"
Result: Learned how staging works and how only staged files are committed.

5. Ignore Them

Command used: nano .gitignore
Command used: git add .gitignore
Command used: git commit -m "Added .gitignore"
Result: Learned how to ignore unnecessary files using .gitignore.

6. Remove Ignored Files

Command used: git rm --cached file.txt
Command used: git commit -m "Removed ignored file"
Result: Learned how to remove already tracked files after adding them to .gitignore.

7. Chase Branch

Command used: git checkout branch-name
Result: Learned how to switch between branches and work on different versions of a project.

8. Pick Your Features

Command used: git cherry-pick commit-id
Result: Learned how to apply specific commits from one branch to another using cherry-pick.

9. Master

Command used: git checkout main
Command used: git merge branch-name
Result: Learned how to manage the main branch and integrate changes from other branches.
