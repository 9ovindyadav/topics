### git commands : 

#### Basics :
 ```
  > git status                    // check status of working tree
  > git add <file-name>           // into staging area
  > git restore --staged <file-name>   // remove from staging area
  > git commit -m <file-name>     // make a commit 
  > git log         //show all commits
  > git reset <commit-id>    // move all above commits and file changes ...out of staging area
 ```

#### Stash :
```
  > git stash         // don't commit but keep the changes somewhere
  > git stash pop      // bring back saved changes which are not commited yet
  > git stash cleat      // clear the saved changes which are not commited
```

#### Branch :
```
  > git branch         // shows all the branches
  > git branch <branch-name>      // create new branch
  > git checkout <branch-name>      // moves the HEAD pointer to new branch
  > git merge <branch-name>      // merge the new branch to main 
```

#### Remote :
```
  > git remote -v         // shows all the URL or remote we added
  > git remote add <remote-name> <url>      // add new remote
  > git remote rename <old-name> <new-name>      // rename remote url name
  > git clone <url>
```

- Types of remote :  

    1. origin : Your personal fork or copy of a repository. You have read and write access to the origin.

    2. upstream : The original repository from which you forked. It represents the main project repository and is typically read-only for you. You can pull or fetch changes from the upstream repository.


```
    > git fetch --all --prune
    > git reset --hard upstream/main

    > git pull upstream main
```
**This commad only fetch new commits in your local system to see new commits in github repo you have to push the new commits**

### Note : 
- A single branch can create one pull request only 
- Never commit on the main branch directly


### Merge conflict : 
- when two person changes the same line of code and creates a pull request then it ocurs.
- it is resolved manually .
 


 ### Github CLI commands


```
   > gh auth login    // to login to github in cli
   > gh repo list     // list all the repo from your github profile
   > gh repo create   // create new repo 
   > gh repo edit    // to edit repo

```



