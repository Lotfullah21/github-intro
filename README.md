## Version Control

- a system that keeps record of all changes and modifications in to files for tracking purpose
- it is called source control
- there are two types of version control system
  - centralized: contains a server and a client.
  - distributed: every user a server not a client.
- few advantages of version control
  - colloboration: as a developer, it is what we do. working in a team to build a product.
  - efficiency:
  - revision history: ability to see the changes and revert back to the previous version of the code
  - we can see when and who changed or add a new feature

## cheat sheets for command line

- 1: touch filename.extension // creates a new empty file
- 2: code filename.extension // opens the file in vs-code

### Unix commands

- ##### Flags: to get more details and add more functionalities to our command,we use flags like(-l, -la, ...)
- ls // print all current list of directories.
- ls -l // lists all directories along their write and read operations in list structure
- pwd // print the current working directory
- mv directory toThisDirectory
- cat file.extenstion // returns content of the file
- less file.extension // read the file
- wc file.extension -w // returns word count of the file.

#### files

- link files always starts with l.
- standard directory always starts with bin,dev
- standard files starts with \_, like \_rw_r\_\_
- lesss

## Repository:

- a central location in which data is stored and managed.

# Git and GitHub

## Git

- a version control system for tracking of all changes to files within a project

## GitHub:

- a **cloud** based hosting service that let us manage Git repository from the user interface
- .git inside a repository is a hidden folder that keeps track of all changes.

### Git WorkFlow

- Git uses workflow which can be broken in three stages.
- Modified -> Staged -> Commited
  - adding, removing, and updating any file inside the repository is considered a modified state.
  - to track a file, filed needs to be putted in staging area, in this stage any modification is tracked.
  - to save the file and have a snapshot of all changes, the files will be putted in commiting stage.( Commits are created with the git commit command to capture the state of a project at that point in time.)

### How to clone a directory ?

- use git clone <https-link>

### How to add changes and rull of changes in there

- use git clone to get the repo
- use 'git checkout -b files/adding' to add a new branch and go chage to that branch
- 'git add .' to add everything up to now
- 'git commit -m "message"' to put your message out there
- 'git push -u origin branchName' to push all the changes.

### How to push a code from a local file to a repo

- use git init

### Can we create a creaet a repo our local machine

- use something great
-
