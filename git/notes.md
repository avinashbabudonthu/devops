## Revert specific commit
* There are a couple of ways to "undo" commits in Git. The "reset" command, for example, allows you to restore your project at any previous revision - effectively "undoing" all the commits that came afterwards
* A different situation, however, is when you want to undo the effects of only a certain commit - and not discard any commits that came after that one. This is a classic scenario for the "revert" command
* Using the revert command doesn't delete any commits. Quite the contrary: it creates a new revision that reverts the effects of a specified commit
* Just use the revert command and provide the commit you want to "undo"
```
git revert 0ad5a7a6
```