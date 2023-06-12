# Day 6

## Agenda

### Theory

- What are git branches?
- Why are branches important
- important commands and syntax

### Practical

- Recap git
- experiment with merging

---

## Git Branches

In a nutshell, Git branches allow developers to diverge from the master/main branch by creating separate branches to isolate code changes. The default branch in Git is the master/main branch and any other branch we create is referred to as a feature branch and we have the permission to name it whatever we want (this will be our workflow for the next year). With branches Multiple people can be working on new ideas in parallel and not affect the main branch.

**side info**

- If you initialize you repository locally, the default branch will be called master.
- GitHub replaced the term "master" on its service with a neutral term like "main" to avoid any potentially offensive language.
- With git the default is still master.
- Override this with `git config --global init.defaultBranch main`

> Visual example of a simple clean branch back to main:
> ![git fast forward merge](./images/FastForwardMerge.png)

> The real world example where there are lots of different variables:
> ![git branch](./images/git-branches.png)

### Why Branch

Branches allow multiple people to be working on new ideas in parallel and not affect the main branch. Eventually the developer might be finished with their feature, in which case they might want to merge (include all the changes in the main codebase "main branch"). Although if the developer maybe tried something out and it didn't work or is no longer needed, the developer can move back to the main and delete the branch without affecting anyone work.

### (HEAD -> master) ?!?!?

HEAD is simply a pointer that refers to your current "location" in your repository.

<br/>

## External Resources

---

- [Learn Git Branching visually](https://www.atlassian.com/git/tutorials/saving-changes)
- [Git and Github Visualized (video about the game in the link above)](https://www.youtube.com/watch?v=p384Hw2eewA)
- [What is Git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F#what_is_git_section)
- [Saving changes](https://www.atlassian.com/git/tutorials/saving-changes)
- [Git Behind the Scenes: How Does Git Work (video)](https://www.youtube.com/watch?v=gzJk1ruqSok)
- [Deleting your git commit history without removing repo on Github](https://www.willandskill.se/en/deleting-your-git-commit-history-without-removing-repo-on-github-bitbucket/)
