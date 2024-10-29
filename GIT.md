# GIT Cheatsheet

## Common Tasks

Change to specified branch: 
```bash
git checkout branch_to_checkout 
```

Pull a specific branch:
```bash
git pull origin branch_to_pull
```

Create a new local branch:
```bash
git checkout -b my_new_branch
```

## Common Workflows

Change repository back to the most recent commit: 
```bash
git reset --hard HEAD # Discard all local changes
git clean -fd # Remove untracked files and directories
```

Delete local and remote branch:
```bash
git checkout mainbranch
git branch -d branch_to_delete # use -D to force
git push origin --delete branch_to_delete
```
