This is for my reference::: basic----------------------------------
git status	Check current branch and changes
git add <file>	Stage a file for commit
git commit -m "message"	Commit staged changes
git push origin main	Push to remote repository
branches----------------------------------------------------
git branch                      # List branches
git checkout -b new-feature     # Create & switch to new branch
git merge new-feature           # Merge branch to main
git branch -d new-feature       # Delete branch
Undo changes------------------------------------
git restore <file>              # Discard unstaged changes
git reset --hard HEAD           # Reset to last commit (CAUTION)
git revert <commit-hash>        # Safe undo for pushed commits
log---------------------------------------------------
$ git log
Lists version history for the current branch
$ git diff [first-branch]...[second-branch]
Shows content differences between two branches

$ git reset --hard [commit]
Discards all history and changes back to the specified commit
