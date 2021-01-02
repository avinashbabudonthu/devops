# Git Commands

* Git version
```
git --version
```

* Overview of all useful commands
```
git help
```

* Complete list of all git commands
```
git help -a
```

* List all git concepts
```
git help -g
```

* Clone git repository
```
git clone repository-url
```

* Clone a repository from remote to local with specific branch_name
```
git clone --branch branch_name repo_url
```

* Current branch
```
git branch
```

* Check all branches
```
git branch --all
```

* Merge branch-1 to current branch
```
git merge branch-1
```
```
Example: Merge master to develop
switch to develop - git checkout develop
merge master to develop - git merge master
```

* Pull latest changes from current branch
```
git pull
```

* Make all files ready to commit. Add all files to staging
```
git add *
```

* Add all files with extension .java ready to staging
```
git add **/*.java
```

* Add all files with extension .java and .html ready to staging
```
git add **/*.java **/*.html
```
* Make all files under src/main/java folder ready to commit (add to staging)
```
git add src/main/java/*
```
* Commit changes to local repository
```
git commit -m "commit message"
```
* Push the changes to current branch. Send all commits from local repository to remote repository
```
git push
```
* Push changes to master branch
```
git push origin master
(or)
git push -u origin master
```
* Push specific branch to your remote repository
```
git push origin [branch_name]
```
* Push all branches to your remote repository
```
git push --all origin
```
* Changed files and those you still need to add or commit
```
git status
```
* Revert all local changes
```
git reset --hard HEAD
```
* If you haven't connected your local repository to a remote server, To add a remote server to a local repository
```
git remote add origin [repo_url]
```
* Create a new local repository
```
git init
```
* Create new remote repository and check in local new repository to remote repository
	* Create new repository in github website
	* Copy new repository URL
	* Go to new project location in command prompt
	* git init
	* git add *
	* 