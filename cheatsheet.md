
command | description
--|--
git init | initializes a directory as a git repository
git remote -v | shows the current remote repository addresses the local repository can make requests to
git remote add [nickname] [address] | adds a remote repository [address] with a [nickname]
git remote remove [nickname] | removes the remote repository address with the [nickname]
git add [file] | prepare the changes in [file]
git commit | creates a snapshot from the prepared changes and adds the snapshot to project history
git push [nickname] [branch] | pushes the history of work to the [branch] of remote repository with [nickname]
git pull [nickname] [branch] | pulls the history of work from the [branch] of remote repository with [nickname] and merges it into the local repository
git status | shows the current status of changes according to git
