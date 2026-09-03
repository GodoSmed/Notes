# Git
STATE: I
SOURCE: ~

## Basics

### What is it?


### How does it work?
**Initialize an empty repository**
```bash
git init `repositoryName` 
```
## Code Areas
**Working (Directory)**
Here, changes are not yet tracked by Git. Until they move to the next area:

Add changes to staging area
```bash
git add `directory/fileName.ext`
```

**Staging (Area)**
This area holds the changes that are ready to be committed
Check the current status and staged changes:
```bash
git status
```

**Local (Repo)**
This area stores commits/snapshots locally

Make a snapshot to the local repository:
```bash
git commit -m "commit message"
```

Track commits:
```bash
git log
```

See specific changes of a commit:
```bash
git show `commitID` #This ID is shown in the git log
```

Change focus from the main branch to a specific commit:
```bash
git checkout `commitID`
```

Create a new commit that reverts the changes introduced by another commit:
```bash
git revert `commitID`
```

Compare changes between commits:
```bash
git diff `commitID1` `CommitID2`
```

Discard all commits after one specific commit:
```bash
git reset --soft commitID   #commits are moved to the staging area
git reset --mixed commitID  #(default) commits changes remains only in the working area 
git reset --hard commitID   #commits are permanently deleted
```

Return to the main brach (local):
```bash
git checkout main #main branch
```

**Remote (Repo)**
Cloud repository for the snapshots, this service is provided by Github, Gitlab, Bitbucket

Link a local repository with the remote repository:
```bash
git remote add origin <repositoryURL> #origin is the default name of the link
```

Make changes in the remote repository:
```bash
git push -u origin main #in vscodium by default the commit button makes a commit and then a push
```

Load last snapshot/changes (repo):
```bash
git pull origin main #main branch
```

Local and remote have different commit history 
```bash
git pull --no-rebase origin main #safest, do a merge commit
git config --local pull.rebase false #permanent

git pull --rebase #local commit on top of the remote commits 
git config --global pull.rebase true #permanent
```

## Branches
Useful for develop features without affecting the main branch

**Local branch**
Create a branch:
```bash
git checkout -b `branchName` 
```

Create a branch from a specific commit:
```bash
git checkout -b `branchName` commitID
```

**Remote branch**
Upload local branch to the cloud repository:
```bash
git push --set-upstream origin `branchName`
```


### What is it used for?


## Variations & Links


