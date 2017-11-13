# Deleting a file/directory completely (erase from history)
[git filter-branch](https://dalibornasevic.com/posts/2-permanently-remove-files-and-folders-from-git-repo)

# Deleting a remote tag
```
How to: Delete a remote Git tag
November 2009 · #git
You probably won't need to do this often (if ever at all) but just in case, here is how to delete a tag from a remote Git repository.

If you have a tag named '12345' then you would just do this:

git tag -d 12345
git push origin :refs/tags/12345
That will remove '12345' from the remote repository.

```
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

## Seeing some differences between branches
`git log --graph --left-right --cherry-pick --oneline master..feature/clasisecurity_unittests`

From here [Branch X is not fully merged error.](https://stackoverflow.com/questions/7548926/git-and-the-branch-x-is-not-fully-merged-error?bcsi-ac-4d57fec82d0c41f9=271918E500000005WQPJro39QDc/uO36TQRdsJfe1kpGAAAABQAAAC+cQQCAcAAAAAAAABKOAAA=)

# Working with tags

## Delete a remote tag
`git push --delete origin Version-1.0`

and it is probably local also so
`git tag -d Version-1.0`

## Create and push a remote tag
```
git tag -a Version-1.0 -m "Version 1.0"
git push origin Version-1.0
```
