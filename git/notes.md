## Revert specific commit
* There are a couple of ways to "undo" commits in Git. The "reset" command, for example, allows you to restore your project at any previous revision - effectively "undoing" all the commits that came afterwards
* A different situation, however, is when you want to undo the effects of only a certain commit - and not discard any commits that came after that one. This is a classic scenario for the "revert" command
* Using the revert command doesn't delete any commits. Quite the contrary: it creates a new revision that reverts the effects of a specified commit
* Just use the revert command and provide the commit you want to "undo"
```
git revert 0ad5a7a6
```

## Git vs Github vs Gitlab
* Git
	* Version control system
	* Allows us to track changes
	* Maintains hystorical backup like snapshots
	* Allows team based development. Allow teams to work on same codebase simultaneously
	* Flexible. Can work local, devops etc
	* CLI
	* Trunk based development
		* master branch as main branch/trunk
		* we can create as many branches as needed and work
	* We have repo
		* Place where we have our code
		
* Github and Gitlab
	* Hosted Git in cloud
	* Web
* Reference
	* Youtube - https://www.youtube.com/watch?reload=9&v=wpISo9TNjfU&ab_channel=IBMCloud