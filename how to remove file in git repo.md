# Git - how delete file from remote repository

If you want to push a deleted file to remote

`git add 'deleted file name'`

`git commit -m'message'`

`git push -u origin branch`


If you want to delete a file from remote and locally

`git rm 'file name'`

`git commit -m'message'`

`git push -u origin branch`

If you want to delete a file from remote only

`git rm --cached 'file name'`

`git commit -m'message'`

`git push -u origin branch`


--ref--

https://stackoverflow.com/questions/9701238/git-how-delete-file-from-remote-repository