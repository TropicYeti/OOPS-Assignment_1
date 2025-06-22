# Questions

**1) List three major control software for software engineering.**

- Git
- Subversion
- Ansible

**2) What are the main advantages to using Git in your software development, and how is it useful for game developers.**

The useful part of git is that it easily keeps track of all files and keeps a record of changes as well, making it easy to revert changes if need be.

**3) Define the following terms in relation to Git. Branch, Pull, Push, repository, working, copy, merge**

- Branch: A git branch acts as a seperate workspace that can connect to other branches
- Pull: Used to retrieve data from a different repository and downloading it to the local repository
- Repository: A repository is a location where the data of the git is stored.
- Working: A branch of a git that is where work is developed, and not the final product itself
- Copy: Copy, also clone, is duplicating an existing repository and the data within.
- Merge: Merge combines changes from branches into the branch above. this is generally how you add data onto the main branch.

**4) If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.**

The policies and procedures of a company may affect what branches of the git you can access as well as if you can edit in that specific branch at all.

**5) Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.**

- Vim
- Vimdiff
- P4Merge
- IntelliJ

**6) In a merged source code file, how does Git let you know there is a conflict?**

A comparison is made between branches, and data conflicts occur when both files have different aspects in the same location (file).

**7) What are the steps you can take to resolve Git conflicts?**

First, you can open the conflicting files. The areas that are conflicting would be highlighted, and you can edit which areas are clashing.

**8) What does git revert do, and how can you use it?**

Git revert is essentially an undo feature that is safe to use when the desire is to undo work, as it creates a new commit and reverses the previous changes.

**9) What does git reset do, and how can you use it?**

Git reset, like git revert, undoes a change, wheras git revert is limited to the previous changes, git undo rolls back to any previous git commit.

**10) What is the difference between git revert and git reset?**

The key deifference is that git revert can only revert back to the most recent git change, whereas git reset can go back to any different git change that was previously made.

**11) True or False. It is okay to commit broken code to the main branch.**

False

**12) True or False. You should commit related changes. For example, fixing two different bugs should produce two seperate commits.**

True

**13) Describe what is DevOps, how is it useful for game developers?**

DevOps is a methodology used within software development where the focus is on collaboration and efficiency. It's useful as it's purpose is to streamline the time it takes to develop software while mainting reliability.

**14) List what tools can be used with DevOps. Give a brief desription of each one. (At least 3)**

- Git, an open source conrtol system to track changes and collaborate
- Jenkins, an open source automation server that acts as a hub for any stage within the development life cycle.
- Terraform is a tool that manages infastructure resourcs.

**15) What is CI/CD and how can it be used to automate the game development process?** 

Ci/CD is used to streamline the process of software development, by aiming to automate the applications that build, test and deploy