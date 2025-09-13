
# Intialize project
1. git remote add origin [url]: brings the repo from cloud to local

2. git remote -v  : checks the repo if it exists 

3. git branch -M main : change the of existing branch 



# While working on project

1. git init -> initialize an existing directory as a Git repository

2. git status -> show modified files in working directory, staged for your next commit

3. git add . -> add a whole change as it looks now to your next commit (stage)

3. git add [learning.md] -> 

4. git rm --cached [file name]


## Extra 
-> You made a change 
-> git status -> to check the changes
-> if only one change go with `git add .` or if multiple changes and feels like alot to work on the other changes as well `git add [fileName]`
-> commit your message what changes you've made `git commit -M "add explore section"(crucial)
-> `git push -u(upstream) origin main` => `git push`


```bash
git status
git add . - git add fileName
git commit -M "add explore section"
```
