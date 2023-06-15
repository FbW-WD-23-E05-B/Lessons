# Review

---

## Shell

### List off basic terminal commands and what they do:

- man (--help): open the manual on the commands
- cd: takes us to a directory -> change directory
- pwd: print working directory -> show us where we are
- mkdir: makes a new directory
- touch: makes a new file
- mv: moves file to new directory && renames files
- cat: shows us the text content of a file in the terminal
- rm: removes a file or directories (with flags/options)
- nano: editing the file/opening the file
- ls: list all the files and directories
- cp: copying files/directories
- less: read the content of a text file (opens the content in a seperate window && allows us to do more, for example searching and changing pages)
- clear: clear the current terminal (caches the content)
- rmdir: remove directories (empty directories)
- apt: packager manager -> built in with ubuntu
- sudo: super user do -> gives us admin rights

### Will rmdir remove a filled directory?

No, rmdir only works on an empty directory

### What does rm -rf do?

Forcibly removes all files and folders inside a directory/ or just a file.

### What is a markdown file and how is it different from a markup file?

- Light file, structured format
- markup (HTML/XML) -> light version markdown (md)
- easily format text on the web
- common use case is for documenting projects

---

## Git and Github

### What is Git?

- **version control system**
- Timeline (stages of our work that are trackable) -> version control
- different types of version
- locally - _distributed_

### What is Github?

- A website that hosts git repositories

### What is adding and committing? Is there a difference?

- 3 different workflows
- changes, staging, committing
- after changes you need to add (technically you are always adding)
- then you will commit to the repo
- Both add and commit at the same time 'commit -am ""`
- Difference: git add (staging the file/files that have changes or that you want to stage), git commit (committing your work, saving a timestamp/mark in your git history)
- _good commit message_: descriptive, to the point and short

### What is a branch?

- parallel branch (to the main)
- copy of the main, work on this new copy/moving ahead, then we add the copy to main and make a new version of main
- branches of tree -> make changes without disturbing others work, then move it into main
- Take a copy (isolate it), allowing more people to work on the same project
- branch -> a pointer to a snapshot (commit) of your changes

### What does the command git branch do without any options/arguments?

List branches that you have locally (show which branch your on)

### Two ways to create a branch and move onto it in one command:

git switch -c [nameofbranch]
git checkout -b [nameofbranch]

### What is the difference between local and remote repositories?

    Local repo:

- your the only person who has the repo / the repo resides on your computer
  Remote repo:
- The repo reside online/hosted (github), all team members have access to it

---

## General (extra)

### Workflow

- we should keep the main clean, make branches and then try to merge those branches with github into the main
- this is a workflow
