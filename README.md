# IECSE-ML-WinterProject18
Repository for IECSE Machine Learning Winter Project 2018, contains the resources and solutions to the tasks given during the project.

# Instructions
 - Create a new branch with your name using the command `git checkout -b <branch-name>`, with branch name in format
 	`<first-name>"-"<last-name>`. eg.- `git checkout -b Rohan-Sakhuja`.
 - All commits should be made to your own branch, **Never commit to master**. To prevent this always check what branch you're on before committing any changes, command to check current branch `git branch`, command to checkout(change to) a branch, `git checkout <branch-name>`.
 - To pull solutions after they are uploaded to master, change branch to master and do a git pull.  
 	`git checkout master`  
 	`git pull origin master`
 - Steps to submit your code.
 	* Add files to be committed using the command `git add .` (the "." after add means all files in the current directory will be added)
 	* Add a descriptive commit message for the same. Command- `git commit -m "<msg>"`.  
    Format - `Task #<task-no.> : description`. Mention any errors or issues in the code in the commit message, if any.
 	
  * Finally, push your code. command - `git push origin <branch-name>`
  

 	```
    git checkout -b Rohan-Sakhuja
 	git checkout Rohan-Sakhuja	// to make sure you are in your own branch
 	git add .	// adds all files and subfolders to be committed in the current directory
 	git commit -m "Task #0: description"
 	git push origin Rohan-Sakhuja
    ```

 - All solutions will be uploaded to master.
 - All tasks will be posted on the [wiki](https://github.com/ramrathi/IECSE-ML-Winter18/wiki).
