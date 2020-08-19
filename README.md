## Learn-github

Created this new repository for analyzing the progress  of my learning.


## Working with Git

### Quick Start

``` git clone <url> ```					
     This creates a directory named open_framework (at your current local file system location), initializes a . git directory inside it, pulls down all the data for that repository, and checks out a working copy of the latest version
  
```git checkout -b <new-branch>``` 		
     This create a branch in a repository
  
```git push -u origin <new-branch>``` 	
     Sync local branch with remote of the repository
  
```git checkout <branch>``` 				
    Checkout branch of the repository
  
```git push origin <branch>``` 		
    Push branch to remote

```git branch -d <branchname>```  
    deletes local branch
  
```git push origin :<branchname>```	
   deletes remote branch

```git init```                   
      initializes the repository
      
```git add .```                
     add those 'unknown' files to the local repository
  
```git add <filename>```
     add particular file to the local repository
  
```git commit -m "message"```          
   commit all changes, edit changelog entry with breif of modification 


### Branching 

```git branch```                        
    This show list of all branches (* is active)
    
```git branch -m <oldname> <newname> ```  
   rename branch

```git branch -m <newname> ```          
   rename current branch

### Merge

```git merge```
     This integrate the branches together


### Delete Project

```git branch -d <branchname>``` 
   deletes local branch
  
```git push origin :<branchname>```	
   deletes remote branch
  



 Above commands can be used for accessing github repository .               
                
