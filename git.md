# Pretty git log

`git log --graph --all --decorate`

# Deleting a remote branch.
-[Stack Overflow](http://stackoverflow.com/questions/2003505/delete-a-git-branch-both-locally-and-remotely/2003515#2003515)

# Working with multiple branches.

Note that git when you do a pull where you have multiple local tracking branches (even if you do --all) only the current branch will have the update/merges done (if they ff). You have to cover the other branches "manually." There are may posts on Stack Overflow discussing this.

# Working with multiple remotes.

## Making sure you are tracking the correct remote branch.
`git branch --set-upstream local_branch remote/remote_branch`

## Pushing changes to a different remote.
`git push <remote> --all`

## Fetching all changes from all remotes.
`git pull --all`

