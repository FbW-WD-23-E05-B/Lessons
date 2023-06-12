# Branching Commands

| Command                                             | Description                                             |
| --------------------------------------------------- | ------------------------------------------------------- |
| `git branch`                                        | List branches (the asterisk denotes the current branch) |
| `git branch -a`                                     | List all branches (local and remote)                    |
| `git branch [branch name]`                          | Create a new branch                                     |
| `git branch -m [old branch name] [new branch name]` | Rename a local branch                                   |
| `git branch -d [branch name]`                       | Delete a branch                                         |
| `git checkout [branch name]`                        | Switch to another branch                                |
| `git checkout -b [branch name]`                     | Create a new branch and switch to it                    |
| `git checkout -`                                    | Switch to the branch last checked out                   |
| `git checkout -- [file-name.txt]`                   | Discard changes to a file                               |
| `git switch -c [new branch name]`                   | Create a new branch                                     |
| `git switch [existing branch name]`                 | Switch to another branch                                |

<br/>

> The "switch" command is relatively new (added in Git v2.23) and provides a simple alternative to the classic "checkout" command..
>
> It has a very clear and limited purpose: switching and creating branches!

<br/>
