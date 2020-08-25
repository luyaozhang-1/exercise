# Git commands cheatsheet
|Command|Description|
|--|--|
|git add .|Change the files in current directory to staged.|
|git commit -m|Commit the staged files to local repository.|
|git push origin|Push the commits to master repository.| 
|mv A B|Chang the name A to name B
|vi A|Open the file in vi editior. To edit it, press <kbd>i</kbd>. To save the edits and exit vi editor, press <kbd>esc</kbd> to exit the editing mode, and then press <kbd>:</kbd>, then enter <kbd>x</kbd>, and press <kbd>enter</kbd>.|
|rm A|Remove the file A|
|git log|Show the log|
|git log --oneline|Show each entry in one line.|
|git tag -a A -m B|Add a tag A with B as the description.|
|git tag|List all tags|
|git checkout tags/A|Check out tag A.|
|git push origin A|Push tag A.|
|git checkout -b A|Create branch A and move to the branch.|
|git branch|Show all the branches|
|git push --set-upstream origin A|Push branch A to the remote repository.|s
|git branch -d A|Delete branch A.|
|git stash|Create a new stash.|
|git stash list|Show the most recent stashes.|
|git stash pop|Rstore the changes to the most recent stash on the list.|
|git stash save "A"|Save the stash under the name A.|

**Note** Git pull is to pull back the remote repository to your local repository. *git pull* covers both *git fetch* and *get merge*.

This is the conflict.