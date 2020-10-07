# 2020-10-07-git_collab-ben

Git collaboration class with Daniel Chen @chendaniely

- [install git](https://carpentries.github.io/workshop-template/#git)
- [git cheatsheet](http://swcarpentry.github.io/git-novice/reference)
- [git workflow](https://chendaniely.github.io/training_ds_r/help-faq.html)

- `git clone <URL>` downloads the repo from the URL to your computer.  
  - Make sure you are not already in a git repo when you clone
  - Best practice is to have a git folder and then your repos inside that folder

## Branching

- keep your temporary works in a separate space from working code

`git branch` show local branches and current branch
`git branch -a` show a local and remote branches
`git log --oneline --graph`

### how to make a branch

- `git branch <branch name>` create the branch
- `git checkout -b <branch name>` create and check out the branch in one step
- wherever head is, the new branch will be created right there
  - head is the point in your git history you are looking.  most commonly it is the most recent change but really it is just a  reference location where you are

### how to move between branches

- `git checkout <branch name>` switch to the branch you specified
- `git status` show files and current branch

### how to send between local and origin

- `git push origin <branch name>`
- bfmcneill@githubuser.noreply.com


### delete local branch

`git branch -d my_branch`

### list remotes

`git remote -v` list the remotes


`git fetch --prune` delete any local commit tree and updating the local tree according to the remote

- fetching is updating log history, not actually impacting files

