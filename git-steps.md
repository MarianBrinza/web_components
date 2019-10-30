1. make git repo
2. make local folder
3. run git init in local folder
4. stage local files
5. commit local files
6. run:  `git remote add origin <remote repository URL>`
7. verify that the remote repo was added: `git remote -v`
8. push to new repo: `git push origin master`
9. i think this should run instead of 8: `git push --set-upstream origin master`, 
to be able to always push to remote
10. fetch changes from remote: `git pull`