<!-- Write your notes here -->
 fix/git-notes-jigisha
### 8.
Pull requests are raised in order to enable any changes made to the code to be reviewed by other collaborators of the repository before it is merged with the main repositories. This lets us tell others about the changes that we have pushed to a branch.

### 10.
The git command to create a <b>new branch</b> is:

    git branch <branchname>

The git command to <b>switch to a branch</b> is:

    git checkout <branchname>

The above commands can be merged into a single command:

    git checkout -b <branchname>

Switching to a <b>previous/parent branch</b> can be done using:

    git checkout -

### 11. 
A <b>new remote</b> can be added to our repository using the command:

    git remote add origin <urlofrepo>
There can be multiple remotes, the primary one is called "origin". 

### 12. 
The git command to view the <b>status of changes</b> to a repository is:

    git status

The git command to view the <b>commit history</b> is:

    git log


* 1. 
 
        Verison Control System : manages changes to documents, computer program. It is a way to track the changes in code made, who made the changes and what all changes were made  

* 3. 

        Branches are created from the main stable branch when we are adding a new   feature or making changes to the exisiting features
        These changes can break the code, therefore to keep the main branches safe from our possible unstable code and for easy reviewing by other contributors upon merging.


*  4.  

        fork is creating a copy of the exisiting 
        independent of the original repository and can persist even after the original repo is deleted
        branch is set of commits within a repo - they cannot exist without the repo

* 7. 

        1. git pull - to get the changes made in the original repo, to keep our branch up to date ,merges the changes made in the original with our own repo

        2. git fetch - does not merge the changes
        git fetch --dry-run gives the summary of commits/ deletions/ updations 

* 13.

        cd  - change directory 
        cd folder_name : changes to folder_name 
        cd .. or cd -: goes back to the parent directory

        mkdir - make directory

        ls - list file
        ls -a : for all files including hidden files
        ls -l : list all files with permissions,name of creator etc

        vi file_name : to create new file (if it does not exist) and edit it 

        cat file_name: to see the content of the files

        pwd: present working directory
