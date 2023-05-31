# Shell vs Terminal & Scripting Language

Shell -> Program which actually process the commands and returns output.
Terminal -> Refers to a wrapper program which runs the shell.
Scripting language -> Is a programming language that employs a high-level construct to interpret and execute one command at a time.

Scripting languages include:

- zsh -> bash but with a few added commands
- oh-my-zsh -> loads of extra commands, cool themes and easy personalization
- bash -> **focus** some commands not found on zsh

## **Basic shell Commands**

> open-terminal-keyboard-shortcut: **Ctrl + Alt + t**

<br />

## **Basic understanding**

- The Prompt: The input field in a text based UI. When we see the prompt we will be able to enter a command.
- Command structure:

```bash
command -options arguments
```

- Case matters: Date vs date, one is a valid command one not. This also applies to options and arguments.

<br />

## **root directory? root home directory? user home directory?**

There are two types of users in a Linux system. The First one is the root user, also known as super user, and the other one is the normal user.

The root user has the infinite power and can do anything in the system, while the normal user has some sort of restrictions and can't perform all the operations that the root user can perform.

- **`/`** is the top level directory, which is known as root directory
- **`~`** user home directory, (Default current working directory when opening new terminal session)
- **`/root`** root home directory. it is the same of your user home directory but for the root account

> You can open ubuntu file manager as root user by typing **`sudo nautilus`** in your terminal

<br />

### **01. man & --help**

Both of **`man`** and **`help`** are used to display the user manual of any command that we can run on the terminal

Syntax:

- **`man [command name]`**
- **`[command name] --help`**

> without the square brackets `[]`

How to understand the synopsis:

- sometimes you will have options display like this: `[Options]` -> the sqaure brackets make it options
- sometimes you will have arguments/options displayed like this: `Arguments` -> this means the arguments or options need to bew there
- finally you could have a `...` -> this means that you can put in multiple arguments or options at a time.

### **02. pwd**

When you first open the terminal, you are in the home directory of your user. To know which directory you are in, you can use the **`pwd`** command. It gives us the absolute path, which means the path that starts from the root. The root is the base of the Linux file system. It is denoted by a forward slash( / ). The user directory is usually something like "/home/username".

<br />

### **03. ls**

Used to know what files and directories are in the directory you are in.

> **Linux commands** can be used in combination with **Flags** to modify the behavior of a command

Some examples about **`ls`** with Flags:

- **`ls -a`** lists all the hidden files
- **`ls -r`** lists all files in reversed order
- **`ls -R`** recursively lists sub-directories
- **`ls -l`** displays the long format of the files
- **`ls -lh`** displays the long format of the files, but it shows the sizes in human readable format

<br />

### **04. cd**

The **`cd`** command, which stands for "change directory", changes the shell's current working directory

##### Absolute/Relative Pathnames:

- Elements of a pathname are separated by a /
- A pathname is absolute if it is described in relation to root
- Absolute pathnames always begin with a /

```
user@user-thinkpad-l15:~$ cd public/ 					`Relative Pathnames`
user@user-thinkpad-l15:~$ cd /home/smh/public/			`Absolute Pathnames`
user@user-thinkpad-l15:~/public$
```

##### Change current directory to root directory

```
user@user-thinkpad-l15:~/public/git/linux-tutorial$ cd /
user@user-thinkpad-l15:/$
```

##### Change Current directory to parent or current directory

The current working directory is represented by a single dot `.`
If you type `cd .`, you will change into the current directory, in other words, the command will do nothing.

```
user@user-thinkpad-l15:~/Desktop$ cd .
user@user-thinkpad-l15:~/Desktop$
```

Two dots `..`, one after the other, represent the parent directory or the directory immediately above the current one.

```
user@user-thinkpad-l15:~/Desktop/React$ cd ..
user@user-thinkpad-l15:~/Desktop$
```

##### Switch back to previous directory

```
user@user-thinkpad-l15:~/Desktop$ cd -
/home/zkh/Desktop/React
user@user-thinkpad-l15:~/Desktop/React$
```

##### Move to users home directory from any location

```
user@user-thinkpad-l15:~/Desktop/React$ cd ~
user@user-thinkpad-l15:~$
```

```
user@user-thinkpad-l15:~/Desktop/React$ cd
user@user-thinkpad-l15:~$
```

<br />
