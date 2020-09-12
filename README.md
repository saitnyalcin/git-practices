# Best GIT Commands
Useful git commands when you feel that you need them to stay away from having more trouble with the repo

## Replace with new Remote Branch
`git branch branch_name --set-upstream-to your_new_remote/branch_name`

## Check your current remote branch name
`git branch -vv`

## Check your current remote name
`git remote -v`

## Change a Git Remote’s URL
`git remote set-url origin git@gitserver.com:user/repo_name.git`

## To delete your remote branch
`git branch origin --delete fix/authentication`

## Check your current remote name
`git remote -v`

## To get the metadata
`git fetch`

## To fetch codebase locally
`git pull`

## Change to my branch
`git checkout feature/myfeature`

## To make modified files to be ready for commit and set a commit message(info)
`git add .`
`git commit -m "my commit message"`

## Push the committed changes to the working remote branch
`git push`

## Change the branch to the master branch
`git checkout master`

## To make sure master branch is up-to-date
`git pull`

## Merge the recent change to master branch locally
`git merge feature/myfeature`

## Push your new/not branch to the remote repository when you make your first push
`git push -u origin feature_branch_name`
