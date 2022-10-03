# python-demo

1. mkdir <folder> to create a new folder that will contain your project
2. git init  
   initialize a git repository in the root of the folder
3. finish your demo project, here is a class about day and event.
4. git status to see which files git knows exist.
5. git add <file> to include in what will be committed and use git status again to check if your files are put in stage
6. git commit -m "comments about your project" to let people who see your change later understand.
7. git checkout -b <my branch name> if you want to change your project but worry about making changes to the main project while developing the feature.


## create a new repository
github--new repository--create repository
1. you need a SSH key first. 
ssh-keygen -t rsa -C "youremail@example.com"
sign in github--SSHkeys--create random title you like--cp id_rsa.pub's content in the text field.--click "add key"
2. git clone + SSH, copy SSH from your new repository. (attention: Github nolonger support username-passord mode, instead, you need a token to use HTTP URL)
or git remote set-url origin git@github.com:hazelduan/python-demo.git


## submit your code
1. In order to get the most recent changes that you or others have merged on GitHub, use the "git pull origin master" or "git pull" command(mine is main)
2. git add <>
3. git commit -m "  "
4. use the git log command again to see all new commits.
5. git push origin demo
6. create your new pull request to alert a repo's owners that you want to make some changes to their code. This will not be created automaticly.
7. Merge your change in Github
