# Git and Github
#github #release #obsidian 

## Creating a Repository

1. In terminal, set the user credentials for your github account
	```bash
	git config --global user.name "USERNAME"
	git config --global user.email "EMAIL"
	```
2. In terminal, navigate to the directory you want to turn into the repository
3. In that directory run:
	```bash
	git init
	
	git add .
	
	git commit -m "initial commit"
	```
4. In a browser create a repository for use
	- Once create there will be a URL copy this.
5. In terminal run:
	```bash
	git remote add origin https://github.com/USERNAME/REPO.git
	
	git push -u origin master

	```
	This might prompt you for your user credentials. In this case enter your username and then a personal access token to continue. 
	
	[How to create a personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) (make sure you give the access token write access)
	
## Updating a Repository

To see all changes:
```bash
Git status
```
use `git add` to stage files or `git add .` to stage all changes.

use `git commit -m "message"` to commit the changes you've made. 

use `git ush -u orgin master` to push to master

## Links
 https://dzone.com/articles/top-20-git-commands-with-examples