# Git: First Steps

[Git](https://git-scm.com/) is a [version control](https://en.wikipedia.org/wiki/Version_control) tool used by developers and technical writers. This tutorial is a barebones intro to git for people who can use the [command line](https://en.wikipedia.org/wiki/Command-line_interface) and [GitHub](https://github.com).

**In this tutorial, you'll learn:**
- What git is
- Why devs use git
- How you can start using git

By the end of this tutorial, you'll be ready to start using git for your personal projects.

---
**Table of Contents:**
- What Is Git?
- How Do You Get Git?
- How Do You Use Git?
- Next Steps
---

## What Is Git?

[Git](https://git-scm.com/) is a [version control](https://en.wikipedia.org/wiki/Version_control) tool used by developers and technical writers. Version control tools help you keep track of the changes that have been made to files.

Version control helps you:
- See what changes were made when, who made them, and why they were made
- Return to an earlier version of the file if you want to undo changes

Using version control is useful for all projects, but it's especially important for projects that have more than one person involved since they may be working on the same files at the same time.

## How Do You Get Git?

Got to the git site to:
- [Download git](https://git-scm.com/downloads)
- [Set up git](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

## How Do You Use Git?

To start using git with GitHub, you'll need to know how to:
- Create a [repository](https://en.wikipedia.org/wiki/Repository_(version_control))
- Add files to the repository
- [Commit](https://en.wikipedia.org/wiki/Commit_(version_control)) changes
- Push changes to a remote repository
- Pull changes from a remote repository

### Create a Repository

A git repository is a folder on your computer where you store your code. To create a new git repository, use the command line to go the folder where you want to store your code and enter the following command:

```
git init
```

This will create a new Git repository in the current folder.

### Add Files to the Repository

Create a file. To add that file to the repository, use the following command:

```
git add <filename>
```

Replace `<filename>` with the name of the file you want to add. You can also use `git add .` to add all files in the current directory.

### Commit Changes

Now that you've added a file to the repository, you can commit that change. A commit is a snapshot of the current state of your code. To commit your changes, use the following command:

```
git commit -m "Commit message"
```

Replace "Commit message" with a short description of the changes you made. Keep it short but informative.

### Push Changes to a Remote Repository

Now that you're made changes on your own machine, you can make sure that your GitHub account reflects those changes. If you don't yet have a GitHub account, [make an account](https://github.com/join) for free. To push your changes, use the following command:

```
git push <remote> <branch>
```

Replace:
- `<remote>` with the name of the remote repository, such as "origin"
- `<branch>` with the name of the branch you want to push to, such as "main"

Now your changes are in the remote repository.

### Pull Changes From a Remote Repository
When you want to make sure that the files you're working on are up to date with files in the remote repository, you'll need to pull from the remote repository. To pull changes, use the following command:

```
git pull <remote> <branch>
```

Replace:
- `<remote>` with the name of the remote repository, such as "origin"
- `<branch>` with the name of the branch you want to pull from, such as "main"

Now the files you're working on are up to date with files in the remote repository.

## Next Steps
Now that you know what git is and how to use it, you can practice using it with your next personal project.

To learn more, see these resources:
- [Git docs](https://git-scm.com/docs/)
- [Git commands for devs working on a one-person project](https://git-scm.com/docs/giteveryday#STANDALONE)
- [Git commands for devs working on a group project](https://git-scm.com/docs/giteveryday#PARTICIPANT) 
