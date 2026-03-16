# Commands

```bash
git init                                        # Makes a git repo

git add <filename>                             # adds one file to the Stage

git add -A                                     # adds all files not on the ignore to the Stage

git commit -m '<msg>'                          # commits all Staged Files with msg

git status                                     # Hints what to do next / where you are

git log                                        # Log of commits (q quits out of that view)

git checkout -b <branchName>                   # Create and checkout branch

git checkout <branchName>                      # Checkout branch

git merge <otherBranchName>                    # Merge other branch into current branch

git remote add origin <url>                    # Empty Repo on Github gives this url, use HTTPS not SSH

git remote -v                                  # list of all remote urls

git push origin <branchName>                   # Push local branch commits to remote branch

git tag -a <version> -m <message>

git push origin --tags                        # Push the tags seperately

git tag                                       # list all tags

git pull origin <branchName>                  # Fetches and Merges remote branch to current

git fetch origin <branchName>                 # Gets the meta Data about a branch to your local
```