## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a set of commands that can be used in the terminal.
Git is a distributed version control system to keep track of all the changes made to a file on a directory on your copmuter.

2. What is the difference between Git and GitHub?
Git is the actual commands that a developer is running in the terminal of the actual underlying system. GitHub is a cloud wrapper where the repositories are kept. It a place where all the code is stored in GitHub Respositories

3. Why do we create a branch? 
Often there are many people working on different parts of a project and files. We create a branch to have our own copy to work on that can be merged back into the the main branch later. We're able view the differences between branches. A bunch different developers working on the same project at the same time  can cause a traffic jam. A branch takes from the start repository the initial branch  that everbody is working off of and each person makes a copy of it that diverges that each person 
can edit on thier own. As its editied it diverges more and more. At the end of the git branches lifecycle the branches merge back into the main code.

4. What is the purpose of a Pull Request?
The purope of a pull request is to incorporate changes from a remote repository into the current branch.

5. What is the command you can use to switch between branches? For example
you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout -b FIRST-LASTNAME

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch fetches branches from one or more repositories. It grabs or dowloads the objects and tags to complete the histories.
Whereas, git merge joins two or more development histories together. Then git pull actually uses git merge to incorporate changes from 
a remote repository into another branch. 

7. What is a merge conflict?
A merge conflict is when changes an area of a file differently in two branches that are being merged resulting in conflict or an improper merge.
 
8. How do you resolve a merge conflict?
Update one of the files on either branch and run git add on each to mark it as resolved, which opens the proper merge tools being git mergetool then run git status to verify that all conflicts have been fixed. Then run git commit to finalize the merge commit. 
