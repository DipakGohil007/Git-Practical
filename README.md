# Git- Practical Exam

## 1. Pull and Merge difference 
- Make example of pull request and two branch merge event.

1. create a new branch.  

2. Push this new branch. 

3. Create Pull Request on GitHub. 

4. Then admin of master branch can approve the pull request. After that feature branch will be merge with the master branch. 


## 2. Rebase
- Try to rebase feature branch with master branch 

1. push master branch after the commit.

2. create another branch named feature.

3. push this feature branch after commit.

4. Now write this command in feature branch:
```sh
git rebase master 
```

## 3. Change commit message
- Commit push on commit in feature branch and then change commit message

```sh
git commit --amend -m "fixed a bug"
```

## 4. cherry pick
- Pick some commits from feature branch to master branch

```sh
git cherry-pick (commit-id)
```

## 5.  Drop commit
- Remove some commit from feature branch.

```sh
git reset --hard HEAD~2
```
- with this command the last two commits will be removed. 

- To remove the last commit from git, we can simply run git reset --hard HEAD^  

- If we want to remove multiple commits from the top, we can run git reset --hard HEAD~2 to remove the last two commits. 

- We can give the number of commits which we want to remove.
