# python-demo
## Create a new repository
GitHub--new repository--create a repository
1. you need an SSH key first. 
ssh-keygen -t rsa -C "youremail@example.com"
sign in GitHub--SSHkeys--create a random title you like--cp id_rsa.pub's content in the text field.--click "add key"
2. create the repo following the current instruction shown by GitHub authentication which is specific and excellent.
3. set the security options to protect your branch

## connection
create a local repo and connect with your remote repo
1.  mkdir <folder> to create a new folder that will contain your project
2. git init  
   initialize a git repository in the root of the folder
3. finish your demo project, here is a class about day and event.
4. git status to see which files git knows exist.
5. git add <file> to include in what will be committed and use git status again to check if your files are put in stage
6. git commit -m "comments about your project" to let people who see your change later understand.
7. git checkout -b <my branch name> if you want to change your project but worry about changing the main project while developing the feature.
8. git remote add origin https://github.com/<username>/repo_name.git to link with your work repository
9. git push -u origin main to push your first commit to your remote GitHub repository
10. Done! 


## Submit your code
1. In order to get the most recent changes that you or others have merged on GitHub, use the "git pull origin master" or "git pull" command(mine is main)
2. git add <>
3. git commit -m "  "
4. use the git log command again to see all new commits.
5. git push origin demo
6. create your new pull request to alert a repo's owners that you want to make some changes to their code. This will not be created automaticly.
7. Merge your change in Github
