# CREATE REPOSITORY

### How to create repository from your local machine 

**Prerequisites** : 
* git must be installed  ( check it by command *git --version* )
* you should have a account on git hub

**Steps** : 
1. Make a directory as **project_name**
1. Go inside this and make sure to work inside this directory only 
1. when you have completed your project then **navigate to the directory project_name**
1. open a terminal here 
1. now run command **git init** => this will create a .git folder
1. Now go to browser and login to git hub
1. On top right corner of your screen click on ** + ** button 
1. A list will be show on which click the **New Repository** button 
1. then just only add your repository name which matches your **project_name** 
1. Next just click on **create repository**
1. this will take you to your repository and from there just get repository url 
1. url must be there on front page itself or click on *clone repository* and get it from there
1. Again back to your computer's terminal , navigate to project_name directory
1. now run commands as 
	1. **git remote add origin <url_of_repository_created_on_git_hub>**
	1. **git add .**
	1. **git commit -m "any message you want to say e.g. adding new repository"**
	1. **git push -u origin master**
	1. refresh git hub your added files must be there

#### Note. If error comes then run this commands : 
1. now run commands as 
	1. **git remote add origin <url_of_repository_created_on_git_hub>**
	1. **git add .**
	1. **git pull origin master**
	1. **git commit -m "any message you want to say e.g. adding new repository"**
	1. **git push -u origin master**
	1. refresh git hub your added files must be there
