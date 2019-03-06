# git_practice
A repository to practice git command

# How to revert a PR?

* Find the PR you want to revert - Copy the hash

```bash
git checkout develop 
git pull
git checkout -b new-branch-name
git revert -m 1 hash # The default editor will open
git push -u origin new-branch-name
```

* Create a new PR from the branch 
* Merge the new PR
