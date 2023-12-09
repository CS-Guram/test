## Lessen 1 Steps to Initialize a Git Repository:

git init -> initialize a new Git repository
git add . -> Add all the files to the staging area:
git commit -m "Initial commit" -> Commit the changes:

## Pushing to a Remote Repository:

**Assuming you have a remote repository set up (e.g., on GitHub), you can push your code using the following steps:**

1. Create a new repository on your GitHub account.
2. Copy the repository URL.
3. Add the remote repository URL:

git remote add origin <repository-url> -> Add the remote repository URL: https://github.com/CS-Guram/test.git
git push -u origin master -> Push your code to the remote repository:
**====================================================================================**

## Lessen 2

Checking the Status:
git status -> This command shows you the status of your working directory, indicating if there are changes that haven't been committed or if everything is up-to-date.

Viewing the Commit History:
git log -> This command displays the commit history, showing information about each commit, including the commit hash, author, date, and commit message.

**====================================================================================**

## Lessen 3 Branching and Merging:

git branch <branch-name> -> Create a new branch
git switch <branch-name> -> Switch to a branch:
git push origin <branch-name> -> # Push <branch-name> to GitHub

git switch -c <branch-name> -> Create and switch to a new branch
git push origin <branch-name> -> # Push <branch-name> to GitHub
git merge <branch-name> -> Merge branches
git branch -d <branch-name> -> Delete a branch
git branch -> to see all branches
git push --delete origin branch_2 -> psuh delete branch_2 to repository
git diff -> This will display the differences in your working directory.

**====================================================================================**

## Lessen 4 Pulling Changes:

Fetch changes from a remote repository: git fetch
Pull changes from a remote repository and merge: git pull

**====================================================================================**

## Lessen 5 Reverting Changes:

Revert the last commit: git revert HEAD
Revert to a specific commit: git revert <commit-hash>

**====================================================================================**

## Lessen 6 Viewing Diffs:

View changes between commits: git diff <commit1> <commit2>
View changes in the staging area: git diff --staged

**====================================================================================**

## Lessen 7 Tagging Releases:

Create a lightweight tag: git tag <tag-name>
Create an annotated tag with a message: git tag -a <tag-name> -m "Tag message"
Push tags to the remote repository: git push origin --tags

**====================================================================================**

## Lessen 8 Stashing Changes:

Temporarily save changes without committing: git stash
Apply stashed changes: git stash apply or git stash pop

**====================================================================================**

## Lessen 9 Interactive Rebase:

Combine, edit, or reorder commits interactively: git rebase -i <commit-hash>

**====================================================================================**

## Lessen 10 Git Ignore:

Create a .gitignore file to specify files or patterns that Git should ignore.

**====================================================================================**

## Lessen 11 Git Hooks:

Git hooks allow you to run custom scripts at different points in the Git workflow.

**====================================================================================**

## Lessen 11 GitHub Flow:

Learn about Git workflows, such as GitHub Flow, which involves creating branches for features or fixes, opening pull requests, and merging changes.
