<!-- Write your notes here -->
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