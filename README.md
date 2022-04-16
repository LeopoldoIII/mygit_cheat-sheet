
# How to rename a Git commit pushed [source](https://stackoverflow.com/questions/11603473/how-do-you-rename-a-git-commit-pushed-to-github)

```
git reset --soft HEAD~1
git add .
git commit -m "custom message"
git push -u -f origin master
```
