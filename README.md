Starting a server from scratch.

First create a folder mkdir server-login and cd server-login
Step 1:
1)Creating a package.json file. This can be done by
 $npm init

2)Installing basic necessary packages
 $npm install --save express mongoose morgan body-parser

3)Add an index.js file
4)Add a .gitignore and write node_modules inside to make sure we are not commiting node_modules in git

---------------------------------------------------------------------------

Step 2: CREATING AND SAVING IT TO git
1)Follow these steps in https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/

2)So, Once you got some initial code on your local folder say "nodeserverlogin". Create a git repository with same name "nodeserverlogin"

3)Inside your local folder do the following steps
 git init
 git add .
 git commit -m "First Commit"
 git remote add origin REMOTE REPOSITORY URL
 git remote -v
 git push -u origin master

4)Now you can check your saved files inside your git repo
