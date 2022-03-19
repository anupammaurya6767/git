# Local Repository

In the working Directory:

```
   git init                        //to initialise the git 

   git status                      // to get status of the staging area and commits
   
   git add .                       // add all the files of working directory to staging area
   
   git add [filename]              //add that file to the staging area
   
   git commit -m "commit_msg"      //to commit all files from staging area to local repository
   
   git log                         // to get log of previous commits
   
   git checkout [filename]         // to revert back the changes to previous version of that particular file
   
   git diff [filename]             // give difference between cureent and previous version of that file
```

# Remote Repository
 ##  Pushing files to existing repo
    In the working Directoy
    
   ```
      git remote add origin [url of the repository]
   
      git push -u origin master // pushes all files to the master branch of remote repository
   ```
# Cloning a Repository
 In the directory where you want to clone the repo
 
 ``` 
 git clone [url of repository]
 ```

# Branching and Merging

 ```git branch [branch_name]      // creating a new branch
    git checkout [branch_name]    //switch to that branch
    git branch                    // shows the current working branch
    
    // To merge a branch to master branch, in master branch type:
    
    git merge [branch_name]
 ```
 
 # .gitignore
``` 
  // To ignore some files (may be secrets which committing in public repo may be risky):
  // In the working Directory
  
  touch .gitignore
  
  // In the .gitignore file name the files which you want to ignore like this:
```
 
 ```
    file1.txt
    file2
    and so on..
    
    # To add comment in .gitignore file
    
    # use *.txt to ignore all txt files 
 ```
 
