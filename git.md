# How to handle line endings/text encodings.
Can be done by filetype in a `.gitattributes` file.

[StackOverflow Link 1](https://stackoverflow.com/questions/170961/whats-the-best-crlf-carriage-return-line-feed-handling-strategy-with-git)

[Repository with a bunch of gitattributes files](https://github.com/alexkaratarakis/gitattributes)

[GitHub's docs](https://docs.github.com/en/free-pro-team@latest/github/using-git/configuring-git-to-handle-line-endings)

This may not be as big a deal now that most editors that I would consider using on Windows handle unix line endings. I think I'm just going to have to experiment a bit and see what happens.

# Choose your own adventure fix up tool:
[On undoing, fixing, or removing commits in git](http://sethrobertson.github.io/GitFixUm/fixup.html)

# Exec a command against commits in a rebase.
I have a new favourite git snippet and its amazing.
`$ git rebase -i --exec "make CFLAGS='-Werror' e7509a8c03`
It runs make on every commit between e7509a8c03 and HEAD, building the project and stopping the rebase if the build fails. Allowing me to fix the commit and continue

# Keeping a github/gitlab fork up-to-date
Working in a github/gitlab flow, you usually fork the hosted repository and then do work on your fork. However, how do you keep your fork up-to-date with the original repository you forked. The simple answer is remotes.

Add a remote named `upstream` (convention) which points to the original repository. You can then pull, rebase, etc from `upstream` to keep your fork up-to-date.
```
git remote add upstream git://github.com/ORIGINAL_USER/REPO_FORKED.git
```

Don't forget to push your stuff back to your remote forked repo to keep it up-to-date also.

# Useful link
[How to undo almost anything with git](https://github.com/blog/2019-how-to-undo-almost-anything-with-git)

[Git Fixum](http://sethrobertson.github.io/GitFixUm/fixup.html)

[How to Fix a Bad Commit](https://dev.to/guivern/git-how-to-fix-a-bad-commit-4068)

# Deleting a file/directory completely (erase from history)
[git filter-branch](https://dalibornasevic.com/posts/2-permanently-remove-files-and-folders-from-git-repo)


# Delete a remote branch
```
Executive Summary
$ git push -d <remote_name> <branch_name>
$ git branch -d <branch_name>
Note that in most cases the remote name is origin.

Delete Local Branch
To delete the local branch use one of the following:

$ git branch -d branch_name
$ git branch -D branch_name
Note: The -d option is an alias for --delete, which only deletes the branch if it has already been fully merged in its upstream branch. You could also use -D, which is an alias for --delete --force, which deletes the branch "irrespective of its merged status." [Source: man git-branch]
```
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
# Review all you git commits over the last year [Susan Potter's Twitter](https://twitter.com/SusanPotter/status/1475668077819871233)
```
$ git rev-list --author=your@email.address --since=1.year.ago --all

Above is across all branches but if you want only what was merged to main you'd do:

$ git rev-list --author=your@email.address --since=1.year.ago main
```
