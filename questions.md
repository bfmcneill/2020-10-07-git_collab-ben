# Questions

## why did origin/head not move when we sync my_branch with remote?

- origin head will only move on default branch unless you do something wonky

## so even though we delete the branch the graph still shows the work?

- yes, git keeps the commit but the branch reference goes away.  you can also see there is a separate commit for the pull request so you can tell what happened

## does the remote list get maintained from the local .git or is it maintained on the remote too?

when you clone it you only get the origin, any additional remotes are only maintained from local

## what tips do you have for a good commit message?

- what are you adding into the staging area.  the things you are adding really only represent one process...one task you are trying gto update... for example update data pipeline.  What is the incremental think you are working on