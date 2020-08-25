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
|git log --oneline|Show each entry in one line|
|git tag -a A -m B|Add a tag A with B as the description|
|git tag|List all tags|
|git checkout tags/A|Check out tag A|
|git push origin A|Push tag A|

**Note** Git pull is to pull back the remote repository to your local repository. git pull = git fetch + get merge.