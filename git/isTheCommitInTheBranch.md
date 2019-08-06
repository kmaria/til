# To find out if current branch contains the commit

List branches which contain the specified commit:
```
git branch --contains <commit>
```
Lists remote tracking branches as well:
```
git branch -r --contains <commit>
```

First naive option is to use git log, but the grep could result in false positives if git log mentions the commit SHA for reasons, e.g. it's mentioned in a commit message as the result of a port from another branch.
```
git log | grep <commit_id>
```
