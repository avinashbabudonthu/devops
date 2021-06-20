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
git branch -a

git branch --all
```

* switch to another branch
```
git checkout branch-name
```

* Create a new branch and switch to it
```
git checkout -b branch-name
```

* Delete the feature branch from local repository
```
git branch -d branch_name
(or)
git branch -D branch_name
(or)
git branch --delete branch_name
```

* Merge branch-1 to current branch
```
git merge branch-1
```
* Merge master to develop
	* switch to develop
		* git checkout develop
	* merge master to develop
		* git merge master
* Merge master to branch-1
```
git merge branch-1 master
```
* Pull latest changes from current branch
```
git pull
```

* Make all files ready to commit. Add all files to staging
```
git add *

git add .
```

* Add file to staging (ready to commit)
```
git add file-name
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
* Reset local repository and point your local master branch to latest history fetched from remote server
```
git reset --hard origin/master
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
	* git commit -m "commit message"
	* git remote add origin [remote-repository-url]
	* git push -u origin master
	* Enter credentials
* Revert specific file changes
	* git checkout -- file1.txt
	* git checkout -- **/*.java
```
git checkout -- fileName
```
* Configure the author email address to be used with your commits
```
git config --global user.email "test@gmail.com"
```
* Configure the author name to be used with your commits
```
git config --global user.name "User defined name"
```
* Will remove user credential details from local repository
```
git config --local credential.helper ""
```
* List all currently configured remote repository URLs
```
git remote -v
```
* Get commit id
```
git log
```
* Remove files from the staging area
```
git reset HEAD file-name
```
* Remove ignored files
```
git clean -fX
```
* Remove ignored and non-ignored files
```
git clean -fx
```
* Remove un tracked directories
```
git clean -fd
```
* Clean repository to initial stage
```
git clean -x -d -f
```
* Revert specific commit
```
git revert commit-id

git revert 0ad5a7a6
```
* Store git credentials
	* This command will create file named `.git-credentials` in `Users\[username]` folder
	* t9
```
git config --global credential.helper store
git config --global user.name "your username"
git config --global user.password "your password"
```