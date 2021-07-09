# Git Demo
Git is a free and open source distributed version control system, a software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.

## Initialize gitflow
- `git flow init` with Git flow extension
## Revert single commit
- `git log --oneline`
- `git revert 8e4fe41fd05c9b730ce020a425ab59927a9d76f4`
- `git push`
## Revert multiple commits with a single discriptive commit message
- `git revert HEAD~4 --no-commit` 
- `git commit -m "Revert last 4 commmits"`
- `git push`
## Reset local commits
- `git reset HEAD~1`
## Remove local changes and files
- `git checkout .`
- `git add --all`
- `git stash`
- `git stash drop`
## Revert commits and commit history
- `git reset HEAD~5`
- `git push --force-with-lease`
## Stash and re-apply changes
- `git stash`
- `git stash pop`
## Clear stash list
- `git stash clear`
