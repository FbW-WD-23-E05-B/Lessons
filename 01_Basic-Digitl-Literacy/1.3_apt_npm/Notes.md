# Day-04 APT & NPM

## today
### introduction package managers (apt, npm)

- Understanding apt, sudo, snap and npm 

# apt vs snap

- APT, short for Advanced Package Tool, is a package management system used by Debian and its derivatives like Ubuntu. APT simplifies the process of managing software on Unix-like computer systems by automating the configuration, and installation of software packages.


## Update the local list of software repositories
- `sudo apt update` =>this command checks all of the system in the library of linux if there is any upgrading version
- `sudo apt upgrade`=> this downloads the new version of any pakcage if exist 
- The user types another command: `sudo apt install git`.

## Installation of a package

### sudo 
- sudo (SuperUser DO) is a Linux command that allows running commands as another user, typically the superuser, granting administrative level permissions.

## Running a command as a superuser
- `sudo apt install package-name` like `git` which we will install tomorrow :)
- `sudo apt autoremove`  in a nutshell,  helps you keep your system (or library desk in this analogy) clean and free of unnecessary packages (books) that you're no longer using.



## snap 

- Snap is a software packaging and deployment system developed by Canonical for Linux distributions. Snap packages, or 'snaps', are self-contained packages that include the software and all dependencies (tree) needed to run it.


- Snap packages are all everything in one container with all necceessary tools
- updateing automatically
- the installation is isolated 
- reducing conflicts
- heavier package size
- `sudo snap install package-name`
- `snap list`
- `snap remove package-name`
- `snap remove --purge package-name` **--purge**  is for delteing also dependencies tree (no need anyway!)


- Overall, the choice between Snap and Apt for installing Chromium depends on your preferences and requirements. If you want the latest version and a self-contained package with automatic updates, Snap is a good choice. If you prefer stability and a more integrated system experience, Apt is a suitable option.



# npm => stands for Node Package Manager
- It is a default package manager for the JavaScript runtime environment Node.js

- Run `npm init -y` to create a new npm project. This will create a file called **package.json** in your directory.

- `npm install package name`|| `npm i package name`
- `npm uninstall package name `
- `nvm` is a tool for changing nodjs veresions esily and fast
- `nvm install --lts` => it installs the most stable of node version so far
- `nvm use version-node  ` => for example  ` nvm install 19` =>  `nvm use 19`