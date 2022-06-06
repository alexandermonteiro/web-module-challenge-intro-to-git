## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
Git is a DevOps tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.

2. What is the difference between Git and GitHub?
Simply put, Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them.

3. Why do we create a branch?
Creating a new branch allows you to isolate your changes from the master branch. If your experimentation goes well you always have the option to merge your changes into the master branch.

4. What is the purpose of a Pull Request?
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
You can use the git switch - command to undo any changes you make and return to your previous branch. If you instead want to keep your changes and continue from here, you can use git switch -c <new-branch-name> to create a new branch from this point.

Or you could run git checkout main

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Git fetch just "downloads" the changes from the remote to your local repository. git pull downloads the changes and merges them into your current branch. "In its default mode, git pull is shorthand for git fetch followed by git merge FETCH_HEAD ." People, click on the link to interact with the different columns.

7. What is a merge conflict?
A merge conflict is an event that takes place when Git is unable to automatically resolve differences in code between two commits. Git can merge the changes automatically only if the commits are on different lines or branches.

8. How do you resolve a merge conflict?
To resolve a merge conflict, you pull the changes to your local repository and fix them there. 

