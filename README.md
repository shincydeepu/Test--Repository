STEP 1: Create a repository in github. com

STEP 2: Clone this repository to your local computer
            Under the repository , click on CLONE OR DOWNLAOD
            Copy the URL of the repository
            Open GitBash from the folder in the local computer where you want to create the clone
            Type :  git clone and paste the url in this line 
            Press Enter
      This will create a copy of the repository in the local computer
      
STEP 3: Now make changes to the file in the cloned verion of the repository in the local computer and upload [Existing project to github]
            open git bash from the folder where the file is
            git init [Initialise the local directory as a git repository]
            git add .
            git commit -m "Adds an existing file in a repository to remote repository"
            git remote add origin remote-repository-URL [sets the new remote] 
            git remote -v  [verifies the new remote url]
            git push origin master [push the changes in your local repository to git hub]

Step 4: Test










Adding a file to a repository using the command line [from local to remote repository, first time]
            Open Gitbash in the local repository ( The file that needs to be added should be in this local repository)
            git add . [adds the file to your local repository and stages it for commit] [To unstage : git rest HEAD your-file]
            git commit -m "Add existing file" [Commits the tracked changes and prepares them to be pushed] [To remove/modify use git reset --soft HEAD~1 AND comit and add again]
            git push origin your-branch [pushes the changes from local to the remote repository]
       

