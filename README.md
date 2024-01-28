# LearningGitHub01

## Git commands

Check list of branches:
`git branch --all`

Create a new branch:
`git branch mybranch`

Switch to branch:
`git checkout mybranch`

Add files:
`git add README.md`

Commit:
`git commit --m 'update readme file'`

Push:
`git push --set-upstream origin mybranch`

`git status`


`git log HEAD` - View commit history, starting with the commit pointed to by HEAD.
`git reset HEAD~1` - Undoing the last commit and moving HEAD back one commit.


## Checkout and Switch

### Using git checkout
`git checkout master` - switch to master branch
`git checkout -b new_branch` - create and switch to a new branch

### Using git switch
`git switch feature_branch` - switch to feature_branch branch
`git switch -c new_branch` - create and switch to a new branch

### 
`git checkout <commit_SHA>` - Can be used to move HEAD to a "DETACHED HEAD".


## Revert
`git revert <commit_SHA>`


## GitHub CLI (command-line interface)

1. Open [github cli](https://cli.github.com/manual/gh)
2. Run `brew install gh`
3. Run `gh auth login`
- What account do you want to log into? **GitHub.com**
- What is your preferred protocol for Git operations on this host? **HTTPS**
- Authenticate Git with your GitHub credentials? **Yes**
- How would you like to authenticate GitHub CLI? **Login with a web browser**
4. Copy code
5. Open [login device](https://github.com/login/device)
6. Insert code

