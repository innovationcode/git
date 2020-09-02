# Adding an existing project to GitHub using the command line
 
1. Create a new repository on GitHub. (You can also add a gitignore file, a readme and a licence if you want
 Open Git Bash)
2. Change the current working directory to your local project.
3. Initialize the local directory as a Git repository.
  
   ```git init```
4. Add the files in your new local repository. This stages them for the first commit.
  
   ```git add```
5. Commit the files that you’ve staged in your local repository.
  
   ```git commit -m "initial commit"```
6. Copy the https url of your newly created repo
7. In the Command prompt, add the URL for the remote repository where your local repository will be pushed.

   ```git remote add origin remote repository URL```

   ```git remote -v```
8. Push the changes in your local repository to GitHub.

   ```git push -f origin master```
