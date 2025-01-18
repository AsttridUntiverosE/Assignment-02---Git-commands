# Assignment-02---Git-commands

Answer the following questions

1. What command is used to initialize a local git repository?
   git init 
2. What command is used to "download" a git repository from github?
   git clone <repository_url>
3. What is a git remote repository?
   Is a version of your code or project hosted on Github or another servers. You can collaborate with other people
4. What command is used to move changes from the Working Directory to the Staging Area?
   git add .
5. What command is used to commit change in the Staging Area?
   git commit -m ”add file”
6. What command is used to view the status of the repository? Which files are in the Working directory, which files are staged
   git status
7. What happens when you change the contents of a staged file? Does it stay staged, or does it move back to the working directory
   The file remains staged for the earlier changes, but the new modifications are in the working directory, you need to include the new changes with git add.
8. What command is used to view the list of changes in a repository?
   git log
9. What command is used to "sync" a local repository with a remote repository?
   git push origin main
