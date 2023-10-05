# How to create local repository?
```
git init
```
# how to stage files changes?
```
git add <file> //stage single file
git add <file1 file2 file3> //stage multiple files
git add . //stage all changes and this not recommended
git add -e //manually edit the chunk
git add -p //get diff staging changes
```
# How to remote file from stage?
```
git restore --staged <file>
```
# how to track files changes?
```
git commit -m "YOUR_COMMIT_MESSAGE"

```
# How to add remote repo?
```
git remote add origin <REPO_URL>
```
# How to push your changes to remote repository?
```
git push origin main
```
# How to get clone from remote repository to your local machine?
```
git clone <YOUR_REPO_URL>
```
# How to get branch status?
```
git status
```
# How to get repo logs?
```
git log //this command will git all changes logs with commit id,Author,date and commit message
git log //this command will git all changes logs with commit id,Author,date,message and commit changes text
git log --oneline //this command will get logs with short commit id and commit message
```
# How to create new branch?
```
git checkout -b <BRANCH_NAME>
```
# How to switch to existing branch?
```
git checkout <BRANCH_NAME>
```
# How to delete branch locally?
```
git branch -d <BRANCH_NAME>
```
# How to delete the branch remotely?
```
git push origin --delete <BRANCH_NAME>
```
# How to list local branches?
```
git branch
```
# How to merge branch into main branch using merge command?
```
git checkout main
git merge <MERGED_BRANCH_NAME>
git push origin main

```
# How to merge branch into main branch and then delete the branch from local and remote repo?
```
git checkout main
git merge <MERGED_BRANCH_NAME>
git checkout -d <MERGED_BRANCH_NAME>
git push origin --delete <MERGED_BRANCH_NAME>

```
# How to merge branch into main branch using rebase command?
```
git checkout main
git rebase <MERGED_BRANCH_NAME>
git push origin main
```
 
