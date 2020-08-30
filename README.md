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
 
 ### FOUR EYES PRINCIPLE

        The Four eyes principle is a requirement that two individuals approve some action before it can be taken.
        The two-man rule is a control mechanism designed to achieve a high level of security for especially critical material or operations. Under this rule all access and actions requires the presence of two authorized people at all times.

       ###Objective
          
          The objective of the control is to mitigate risks primarily of the following two types:


          Business Execution, adverse outcomes as the result of poor execution of regular business tasks (mistakes, oversights)
         
          Internal Fraud, adverse outcomes as the result of fraudulent action of persons internal to the firm

          Depending on the context, potentially other types of risk may also arise from the absence of this control (e.g. Physical Damage)

     ###Implementation
     
          Implementing this control is relatively simple in document based approval processes. It requires:

                         Adding qualified persons in the approval list
          
                         Double / multiple signatures

          More stringent forms of this control may require that no sensitive operation can be performed without the simultaneous presence of two people (Dual Control).

          An instructional (if extreme) example is the manner in which missile launching crews are organized:

                         Once a missile launch order is received, two operators must agree that it is valid by comparing the authorization code in the order against a Sealed 
          
                         Authenticator (a special sealed envelope which holds the code)

                         These Sealed Authenticators are stored in a safe which has two separate locks
     
                         Each operator has the key to only one lock, so neither can open the safe alone

                         Also, each operator has one of two launch keys; once the order is verified, they must insert the keys in slots on the control panel and turn them simultaneously

                          As a further precaution, the slots for the two launch keys are positioned far enough apart to make it impossible for one operator to reach both of them at once
                          
                          For additional protection, the missile crew in another launch control center must do the same for the missiles to be launched
     
                          A total of four keys are thus required to initiate a launch.

        ###Examples

          A classic example of implementing "Four Eyes" is in the Credit Approval Process where any credit decision must be reviewed and signed by a second independent person

          In many areas the principle is generalized in requiring a separate review by a different team. An important example is the review any risk models by Independent Model Validation

        
 
 ### BOY SCOUT
 
         Boy Scouts have a rule regarding camping, that they should leave the campground cleaner than they found it.
         
         Good naming can make your code self-documenting and make documentation less important and in some cases even redundant.

Let's think of a simple example.

 ``` int method(int[] array) {
    if (array == null || array.length < 0)
      return 0;

    int integer = array[0];
    for (int number : array)
      if (number < integer)
        integer = number;
    return integer;
  }```

It's pretty easy to determine what this code does, but it would be even easier if we choose better names for the method and variables.


 ``` int min(int[] numbers) {
    if (numbers == null || numbers.length < 0)
      return 0;

    int currentMin = numbers[0];
    for (int candidate : numbers)
      if (candidate < currentMin)
        currentMin = candidate;
    return currentMin;
  }```

I just changed the names, nothing else, it does the same thing (and now even the name implies that it searching the minimum in the array). But now it looks much much better.

To be honest, when I was writing the example of bad naming, I made a mistake. I wrote `number > integer instead of `number < integer` and noticed it only when I changed the names. In such a simple procedure, such a huge mistake just because of bad naming. Imagine what can happen when you work on a huge system!

         
### CLEAN CODE PRACTICES

1 . Keep It Simple

2. Understand Your Code

3. Comments Are Your New Best Friends

4. Don’t Repeat Yourself (DRY)

5. Indent Your Code

6. Naming Convention

7. Explore

8. Use Your Brain

9. Test Runs

10. Practice Your Art


         
        
                
