## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
	Git is an open source distributed version control system. Git stores code remotely on a server as well as locally on the user's machine. Git maintains a history of changes made to a code.
2. What is the difference between Git and GitHub?
	GitHub is a for-profit company that offers a cloud-based Git-hosting service.
3. Why do we create a branch?
	Creating a branch allows for an independent line of work/development.
4. What is the purpose of a Pull Request?
	Pull requests lets us compare branches to see the changes proposed before being committed to the remote repository.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
	git switch allows for switching between branches.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
	git fetch fetches files from a remote repository. git merge merges two branches together. git pull is a combination of git fetch then a git merge, fetching files from a remote repository, then merging them to a local branch.
7. What is a merge conflict?
	A merge conflict results when attempting to merge two branches in which the same line of code has been edited. git cannot decide for itself which version to keep, so a conflict is issued.
8. How do you resolve a merge conflict?
	To resolve a merge conflict, disparate lines of code in the two merging branches are to be edited to match to allow for the merge.
