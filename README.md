# Learn_git

# Code versioning tool 


Initialing 

$ git init <under the project> 

if exits 

$ git status 

Add

$ git add <file>

Commit 

$ git commit -m "<message>"

History

$ git log

$ git log --oneline

Help 

$ git help --all 

$ git <command> --help


Branch ()

$ git branch 

What is it? 

merge juncao 


Creating new branch

$ git branch <name>

or 

$ git switch -c <name>

Go to other version 

$ git switch <name>

$ git push --set-upstream origin <name branch>

* Already on branch master

	Using Merge
	
	$ git merge <name branch>

Deleting branch 

$ git branch -d <branch name>

Git ignore 

creating file

.gitignore 

indicate files or folders that I want git not to put in the repository


Correcting commit message

$ git log --oneline (see)

$ git commit --amend -m  "<new message>"

WARNING!! 

$ git revert HEAD( or HASH) --no-edit (or -m " new message")

$ git revert HEAD --no-edit 


Alterei aqui








