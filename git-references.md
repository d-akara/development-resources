`<remote>` = remote repository name.  Usually **origin** or **upstream**

### Info From GIT
- List remote names and urls
  - `git remote -v`
- List all branches local and remote
  - `git branch -avv`
- List information from remote by querying remote
  - `git remote show origin`

### Delete Something
- Delete branch on the remote repository
  - `git push <remote> :<remote branch>` *push nothing from local to remote, which deletes remote branch*
- Delete multiple obsolete tracking branches
  - `git fetch <remote> --prune`
  
### Recover Something
  
### GIT Config
Remotes and trackingb information stored in `.git/config`
