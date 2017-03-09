# Learning about remote
```
➜  nlp-mayo-storm git:(master)  $ git remote show origin
* remote origin
  Fetch URL: http://tfs:8080/tfs/MayoClinic/IMA/_git/nlp-mayo-storm
  Push  URL: http://tfs:8080/tfs/MayoClinic/IMA/_git/nlp-mayo-storm
  HEAD branch: master
  Remote branches:
    1.0.0-release-branch                                     tracked
    ADD_TOPOLOGY_USERS                                       tracked
    Recreate_1.3.5-RELEASE                                   tracked
    ikp-cerner-parser                                        tracked
    master                                                   tracked
    refs/remotes/origin/feature/update_clinicalmedtagger_ver stale (use 'git remote prune' to remove)
    release/1.3.8                                            tracked
  Local branches configured for 'git pull':
    master        merges with remote master
    release/1.3.8 merges with remote release/1.3.8
  Local refs configured for 'git push':
    master        pushes to master        (up to date)
    release/1.3.8 pushes to release/1.3.8 (up to date)
```

# Pruning remote stuff.
```
git remote prune --dry-run origin
Pruning origin
URL: http://tfs:8080/tfs/MayoClinic/IMA/_git/nlp-mayo-storm
 * [would prune] origin/feature/update_clinicalmedtagger_ver
```

# Pretty git log

`git log --graph --all --decorate`
`git log --graph --oneline --decorate`

[alias]
`lg1 = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all`
`lg2 = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)' --all`
`lg = !"git lg1"`

# Deleting a remote branch.
-[Stack Overflow](http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely/2003515#2003515)

# Working with multiple branches.

Note that git when you do a pull where you have multiple local
tracking branches (even if you do --all) only the current branch will
have the update/merges done (if they ff). You have to cover the other
branches "manually." There are may posts on Stack Overflow discussing
this.

# Working with multiple remotes.

## Making sure you are tracking the correct remote branch.
`git branch --set-upstream local_branch remote/remote_branch`

## Pushing changes to a different remote.
`git push <remote> --all`

## Fetching all changes from all remotes.
`git pull --all`

