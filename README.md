# phase-0-gps-1

phase-0-gps-1


GPS 1.1 git

** commands ** git clone: clones the repo from github touch: creates a file git branch: lists current branches and which branch is current git checkout -b name: creates a new branch and switches to that branch git status: lists the staged and unstaged changes of files git add . : adds all modified files into staging area git commit -m "message": snap shot of the changes made, something like a save preparing for push to github, uses a database number to track the change ls: list contents in directory subl Readme: open readme in sublime text editor

** How git tracks changes **

changes on local machine

create a new file and you are changing it

Add: working stage Working directory: modified the file but those changes are not staged

git add . : stages the changes

staging area: marked a modified file to go into the next snapshot, in it's current version

git commit -m "explain what is being done"

Git directory: commited, data safely stored in your local database