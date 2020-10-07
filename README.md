# 2020-10-07-git_collab-ben

Git collaboration class with Daniel Chen @chendaniely

- [install git](https://carpentries.github.io/workshop-template/#git)
- [git cheatsheet](http://swcarpentry.github.io/git-novice/reference)

- `git clone <URL>` downloads the repo from the URL to your computer.  
  - Make sure you are not alread in a git repo when you clone
  - Best practice is to have a git folder and then your repos inside that folder

## Branching

- keep your temporary works in a separate space from working code

`git branch` show local branches and current branch
`git branch -a` show a local and remote branches
`git log --oneline --graph`

### how to make a branch

- `git branch my_branch`
- wherever head is, the new branch will be created right there
  - head is the point in your git history you are looking.  most commonly it is the most recent change but really it is just a  reference location where you are

## how to move branches

- `git checkout <branch name>`
