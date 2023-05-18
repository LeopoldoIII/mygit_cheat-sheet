# initial branch 
    git init --initial-branch=main

# git config user name/email

    git config  user.name "User"
    git config  user.email "user.rx@gmail.com"


# How to rename a Git commit pushed [source](https://stackoverflow.com/questions/11603473/how-do-you-rename-a-git-commit-pushed-to-github)

```
git reset --soft HEAD~1
git add .
git commit -m "custom message"
git push -u -f origin master
```
# How to Revert a Commit in Git

From visual studio code, install gitLens
With GitLens installed, open your repo and right-click on the commit from the commits view in the side bar to get the 
`Revert Commit` option

<img width="673" alt="image" src="https://user-images.githubusercontent.com/26559577/167340022-a73ba590-b570-4606-a175-02029e95f197.png">

[multiple-github-accounts](https://www.freecodecamp.org/news/manage-multiple-github-accounts-the-ssh-way-2dadc30ccaca/)
