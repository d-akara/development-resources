### References
[Git Flight Rules](https://github.com/k88hudson/git-flight-rules#i-accidentally-deleted-my-branch) The guide for when things go wrong
[Git Tips](https://github.com/git-tips/tips) Most commonly used git tips and tricks

`<remote>` = remote repository name.  Usually **origin** or **upstream**

### Typical workflow
#### Simple: Starting work on existing github project
1. Fork project
1. `git clone <your forked repository url> .` *create local repository in current directory and checkout master branch*
1. `git branch <new branch name>` *create a branch for changes you will perform*
1. `git checkout <new branch name>` *switch working directory files to new branch*
1. `git add ...` *mark changed files and new files you wish to commit to local repository*
1. `git commit -m <message>` *save a verion of all added files in the local repository*
1. `git push` *upload your committed changes to your github repository*
1. Create a pull request from the github page to ask original project owner to merge changes from your forked project.

#### Syncing with updates from remote project
*Starting with a project that has aleady been cloned*
1. `git fetch` *update your local copy of remote branches.  Does not change any local branches*
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
- Restore deleted branch or lost commit
  1. `git reflog` *use to find commit id*
  1. `git checkout -b branch-name <commit id>` *creates new branch from commit*

### GIT Config
Remotes and trackingb information stored in `.git/config`
