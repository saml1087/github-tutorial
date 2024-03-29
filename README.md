# GitHub Tutorial

_by Sam Lee_

---
## Git vs. GitHub
Git is a repository that allows you to have access to git tools, which is commonly used for collaboration with others. This allows people to be able to edit and stage files that will be ready to commit.  
In GitHub, it holds these repositories that can be accessed by others. This is commonly used for collaboration because you will be able to find other's project, which you can access and modify (with Pull Requests) . 

---
## Initial Setup
First, you have to create a directory in the IDE using `mkdir _directory name_`. After changing into the directory, you would be able to initialize the folder.  
In order to initialize a directory you will use `git init` allowing the tools to be accessed in the directory.  
Afterwards, you can create a file using `touch _filename_` . 

---
## Repository Setup
Go to github and log in or create account.
Make a repository by clicking the `+` and then clicking `Create Repository` . 
Afterwards, copy the SSH key, and paste it using `git remote add origin URL`
After having the same directory as the one that you created in github, you would be able to make a repository and push files by using `Git push`.


---
## Workflow & Commands 
Edit your files in the Working Directory.  
Stage your files afterwards by using `git add filename` to the staging area . 
Commit the changes permanently by using `git commit -m "message"` . 
Some basic commands:  
* git init - initializes a directory as a git repository
* git add - adds the file to staging area
* git commit -m - commits the file into the repository and stores it.  