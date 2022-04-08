# VITMAS_TASK0_21BEC0769
BASIC GIT COMMANDS

1)GIT INIT

This command turns a directory into an empty Git repository. This is the first step in creating a repository. After running git init, adding and committing files/directories is possible.

2)GIT ADD OR GIT ADD <filename> for a specific file

Adds files in the to the staging area for Git. Before a file is available to commit to a repository, the file needs to be added to the Git index (staging area). There are a few different ways to use git add, by adding entire directories, specific files, or all unstaged files.

3)GIT COMMIT

Record the changes made to the files to a local repository. For easy reference, each commit has a unique ID.

It’s best practice to include a message with each commit explaining the changes made in a commit. Adding a commit message helps to find a particular change or understanding the changes.

4)GIT STATUS

This command returns the current state of the repository.

git status will return the current working branch. If a file is in the staging area, but not committed, it shows with git status. Or, if there are no changes it’ll return nothing to commit, working directory clean.

5)GIT CONFIG

With Git, there are many configurations and settings possible. git config is how to assign these settings. Two important settings are user user.name and user.email. These values set what email address and name commits will be from on a local computer. With git config, a --global flag is used to write the settings to all repositories on a computer. Without a --global flag settings will only apply to the current repository that you are currently in.

There are many other variables available to edit in git config. From editing color outputs to changing the behavior of git status. Learn about git config settings in the official Git documentation.

6)GIT BRANCH <name>

To determine what branch the local repository is on, add a new branch, or delete a branch.

7)GIT MERGE

Integrate branches together. git merge combines the changes from one branch to another branch. For example, merge the changes made in a staging branch into the stable branch.

8)GIT RESET

Undoes changes to files in the working directory. Resetting lets you clean up or completely remove changes that have not been pushed to a public repository.

9)GIT REVERT

Undoes a committed snapshot. When you discover a faulty commit, reverting is a safe and easy way to completely remove it from the code base.

10)GIT LOG

Shows a log of all actions done by the user.

11)GIT CHECKOUT <name>

Switches to the branch with specified name.

12)GIT REMOVE (git rm)
  
this command deletes the file from your working directory and stages the deletion.
  
13)GIT STASH
  
This command temporarily stores all the modified tracked files.
  
14)GIT PULL
  
This command fetches and merges changes on the remote server to your working directory.
