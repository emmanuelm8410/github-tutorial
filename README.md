# GitHub Tutorial

_by: Emmanuel Marcano_

---
## Git vs. GitHub
* Git- Git is a version control system that would keep snapchots of your code. It does not require github. 
* Github- Github stores code in the cloud, and the cloud is the internet. For example, your cloud 9 account. Github will also track changes that you make for your code and will also show you the time that you have changed any code. it's Easy and collaborates with other files. Git is required for Github. 


---
## Initial Setup
Going to sign up? Go to [Github](www.github.com) 
* Click on the link 
* put in your own information, a username (An email would be better for a username) also your email. 
* It would be best to put in your _HSTAT_ email. 
* To finish up, make your own password and when you are done with the password then you can click "sign up for github"
* To go and start off making your SSH key you would need to be signed into github. 
* Look into the first repository for more information. 

---
## Repository Setup
* Creating an SSH key- **first** you would need to go to your github account and then click on the top right> profile icon> settings
* On the left of the side bar you would see > SSH and GPG 
* __Click__ "new SSH key"


---
## Workflow & Commands
 * `git init` 
 
This command can create a new repository 

 * `git status` 
 
This command tells you where you are in your file or any changes made and tracks it all. 
 * `git add` 
  
 This command adds in all the files into the staging area.  
 * `git add --all` 
 
This command adds in all the changes and even the deleted files 
 * `git commit` 
 
 This command records changes to the repository. The proper way to write `gti commit` is, `git commit -m`. With the "m" you would be able to write a message after the "-m" so it would look like, `git commmit -m "anything you'd like"`. **Always** use `git add .` before you do a commit. 

---
## Rolling Back Changes
* Roll back Changes is like undoing the changes you've made with the power of git 
    If you'd like to practice, [click this link](https://github.com/emmanuelm8410/rollback-scavenger-hunt)
* First before you start to do rollback changes you would need to fork this repository. So in the top right corner you would see the "fork" button. Press on it and you  would see the whole repository for you. 
    