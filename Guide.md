# ADD A PROJECT TO A GITHUB FOLDER
1.	Create a repository in github.
2.	Go to the project file in your computer with Windows Powershell. Sample: “cd C:\Users\AsuS\source\repos\PaypalTutorialFinal”
* Git init
* Git status

3.	Link the local repository to the GitHub Repository
* git config --global user.name “CommanderOtto”
* git config --global user.email ottonegron@hotmail.com
* git remote add origin https://github.com/CommanderOtto/PayPalButtonAspNet.git

4.	Pull files from master (if any)
* git pull origin master

5.	Push files from local
* Git status
* git add -A
* git commit -m “comment on your changes”
* git push origin master

EDIT AND COMMIT A FILE
1.	Check the status of changed files:
* git status

2.	Read the files listed as modified in git status output.

3.	Add the file to be committed/staging:
* git add filename

4.	Check for the status of changes to be committed:
* git status

5.	Commit the change:
* git commit -m “comment on your changes”
* git status

EDIT AND COMMIT MULTIPLE FILES
1.	Check the status of changed files:
* git status

2.	Read the files listed as modified in git status output.

3.	Add several files to be committed/staging:
* git add -A
* Check for the status of changes to be committed:
* git status

4.	Commit the change:
* git commit -m “comment on your changes”
* git status

PUSH FILES TO THE REPOSITORY (SAVE INTO BRANCH)

CHECK COMMIT LOG AND UNDO CHANGES (I need to doublecheck on this part)
1.	Check the log
* git log

2.	Check log entries showing changes by one author:
* git log --author=”otto”
3.	Asdsdf
4.	asdfasd

VIEW DETAILED CHANGES ON FILES AND COMMIT

1.	Check the detailed differences:
* git diff

2.	Add the file to be committed/staging:
* git add filename

3.	Commit the change:
* git commit -m “comment on your changes”

DELETING FILES
1.	In the command-line, navigate to your local repository.

2.	Ensure you are in the default branch:
* git checkout master

3.	The rm -r command will recursively remove your folder:
* git rm -r “foldername”
* git rm -r filename

4.	Commit the change:
* git commit -m "Remove duplicated directory"

5.	Push the change to your remote repository:
* git push origin master

