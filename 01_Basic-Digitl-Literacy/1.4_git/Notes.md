# Day-05 version control system (VCS)


## introduction

-A **Version Control System (VCS)** is like a time machine. It allows you to track the history of a collection of files. It supports creating different versions of this collection. Each version captures a snapshot of the files at a certain point in time.


## Git
- **Git** Git is a  version control system (VCS) created by Linus Torvalds, the same person who created Linux. It's a tool used to track changes in sets of files, usually source code for software development.(developers)


## Git has three main stages (areas) which are:
1. Working Directory
2. Staging Area
3. Repository (Git directory)

- **Working Directory:** This is where all of your files and directories live. It's what you see if you list out the directory contents using a command like `ls` in the terminal. When you make changes to files, those changes are made in your Working Directory.

- **Staging Area:** Also known as the `Index`. This is a staging area where Git tracks changes that you want to commit to the repository. When you add a file to Git using git add, you are moving the changes from the Working Directory to the Staging Area.

- **Repository:** This is where Git permanently stores changes as commits. When you commit changes using `git commit`, you are moving the changes from the Staging Area to the Repository.

### configuration of git 

 - cofigure user name =>> `git config --global user.name   "your user name" `
 - cofigure email =>> `git config --global user.email   " your email" `


# basic commands for git

- `git init`: This command is used to start a new repository.
- `git add <filename>`:This command adds a file to the staging area.
- You can add everything in the current directory using:  `git add .`
- `git commit`: This command records or snapshots the file permanently in the version history with a message describing the change.
- `git commit -m "<commit message>"`
- `git status`: This command shows the list of files you've changed and those you still need to add or commit.

- `git log `  : shows u the history of all commits 
- `git log --oneline ` : shows you the history of all commits in shorter format 
- `git diff <file name>` : shows you the differnces berom current change to previous version of the file 



- lets do some experiment ;)


