### References
- [Git Flight Rules](https://github.com/k88hudson/git-flight-rules) The guide for when things go wrong
- [Git Tips](https://github.com/git-tips/tips) Most commonly used git tips and tricks
- [Git Visual Reference](http://www.ndpsoftware.com/git-cheatsheet.html) Easily see what a command affects

`<remote>` = remote repository name.  Usually **origin** or **upstream**

### Typical workflow
#### Simple: Starting work on existing github project
1. Fork project
1. `git clone <your forked repository url> .` *create local repository in current directory and checkout master branch*
1. `git branch <new branch name>` *create a branch for changes you will perform*
1. `git checkout <new branch name>` *switch working directory files to new branch*
1. `git add ...` *mark changed files and new files you wish to commit to local repository*
1. `git commit -m <message>` *save a verion of all added files in the local repository*
1. `git push -u <remote> <new branch name>` *upload new branch to remote repository*
  1. `git push` *After branch is pushed, 'git push' can be used for all other updates
1. Create a pull request from the github page to ask original project owner to merge changes from your forked project.

#### Syncing with updates from remote origin (your fork) project
*Starting with a project that has aleady been cloned*
1. `git fetch origin` *update your local copy of remote branches.  Does not change any local branches*
   - This is needed to stay in sync with changes others are doing in the remote repository
1. `git merge <other branch>` *execute from your local working branch to merge in changes from another branch*

#### Syncing with updates from remote upstream (original of fork) project
*Starting with a project that has aleady been cloned*
1. `git fetch remote` *update your local copy of remote branches.  Does not change any local branches*
   - This is needed to stay in sync with changes others are doing in the remote repository
1. `git merge <other branch>` *execute from your local working branch to merge in changes from another branch*


### Info From GIT
- List files changed, merges, conflicts and general info
  - `git status`
- List remote names and urls
  - `git remote -v`
- List all branches local and remote
  - `git branch -avv`
- List information from remote by querying remote
  - `git remote show origin`
- List all remote references, tags, branches
  - `git ls-remote`
- List changed files between branches or commits
  - `git diff --stat <branch1>..<branch2>`

### Delete Something
- Delete branch on the remote repository
  - `git push <remote> :<remote branch>` *push nothing from local to remote, which deletes remote branch*
- Delete multiple obsolete tracking branches
  - `git fetch <remote> --prune`
  
### Recover Something
[How to undo (almost) anything with Git](https://blog.github.com/2015-06-08-how-to-undo-almost-anything-with-git/)
- Restore deleted branch or lost commit
  1. `git reflog` *use to find commit id*
  1. `git checkout -b branch-name <commit id>` *creates new branch from commit*
- Undo change already pushed
  1. `git revert <SHA>` *creates a new commit that is the inverse of the given SHA.  Does not alter history*
- Go back to previous version of file(s)
  1. `git checkout -- <filename>` *replace with last committed version*

### Tags
- `git tag <tagname>` *create a tag on local repository*
- `git push <remote> tag` *push tag to remote repository*

### GIT Config
Remotes and trackingb information stored in `.git/config`
