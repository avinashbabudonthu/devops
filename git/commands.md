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