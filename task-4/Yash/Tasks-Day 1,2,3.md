# Task 1:

**1.What do you mean by Git and GitHub?**
*Git* is a distributed version control system which tracks changes to source code over time. It is a command line tool that requires an interface to interact with the world. It stores and catalogs changes in code in a repository. Multiple developers can work simuntaneously with no code conflicts. It uses repositories to store the changes made in source code.

Github is a web-based hosting service for git repository to bring team together. It is a graphical interface and a development platform created for millions of developers. It provides a platform as a collaborative effort to bring teams together.

**2. Why GitHub is so popular and used in most of the projects?**
As it is web service so user can access his project from anywhere and It support all types of files. Through github we can share our code with others giving them the power to make edits on various Git branches. It is so popular and used in most of the projects because of the following reasons:
a)Open, clear communication
b)Public APIs. These allowed others to build upon their work.
c)The right amount of functionality: repo, issue tracking, wiki, GitHub Pages
d)Developer Oriented.

**3. What is a version control system? How Git is a VCS?**
*Version Control System (VCS)* is a software that helps software developers to work together and maintain a complete history of their work. VCS allows developers to work simultaneously and maintain a history record of every version. It doesn't allow overwriting each other's changes.
There are 3 types of VCS:
Local Version Control System
Centralised Version Control System
Distributed/Decentralised Version Control System. 
Git is a Distributed Version Control tool that supports distributed non-linear workflows by providing data assurance for developing quality software Git gives each developer a local copy of the entire development history, and changes are copied from one such repository to another. These changes are imported as additional development branches, and can be merged in the same way as a locally developed branch.

**4. What are the other platforms similar to GitHub?**
The other Platforms similar to GitHub are:
1.GitLab
2.BitBucket 
3.SourceForge 
4.Launchpad 
5.CodeGaint

**5. Why are you interested in learning of Git and GitHub?**
I want to learn Git and GitHub to enhance my knowledge. Learning Git and GitHub will help boost my potential and help me perform open source development.


# Task 2:

##The following is a link to the GitHub Repository I have created: https://github.com/Yash19V/Git-Series

**1.How git workflow works?**
There is only one central repository. Each developer clones the repository, works locally on the code(remote repository), makes a commit with changes, and push it to the central repository for other developers to pull and use in their work.
This workflow employs two parallel long-running branches:
•	Master
•	Develop

The three stages of a file are:
1.Untracked: the file exists, but is not part of git's version control
2.Staged: the file has been added to git's version control but changes have not been committed
3.Committed: the change has been committed

**2.What are the different stages of a git project as commit, add?**
*add*: It is used to move a file from workspace (working directory) to the staging stage (Index), they are tagged for the next commit.
*commit*: It is used to move a file from staging stage (Index) to Local Repository. It is used to save a particular position of our repository so that we could come back later if we ever want to.

**3.Is it possible to do git commit before git add. If you have made any changes? Explain why?**
*Yes*, you can perform git commit command before git add by using: git commit -a command, which is a shortcut in which we can skip the git add command.

**4. Why is git diff used?**
Diff command is used in git to track the difference between the changes made on a file. Since Git is a version control system, tracking changes are something very vital to it. Diff command takes two inputs and reflects the differences between them. It is not necessary that these inputs are files only. It can be branches, working trees, commits and more

**5. Can we leave the commit message as blank?**
*Yes*, we can leave the commit message as a blank. But, generally a non-empty message is preferred because providing a meaningful commit message is part of good development practice.


# Task – 3
## First Pull: https://github.com/codewayy/github_series/pull/5
## Second pull: https://github.com/codewayy/github_series/pull/7

**1. What is meant by the term fork and clone?**
First you fork the repo that you are interested in, so that you have a separate repo that is associated with your GitHub account. Then, You clone the repo and perform your work and You may push it to your forked repo whenever you want.
A fork is a remote, server-side copy of a repository, distinct from the original. 
Fork in git means making a personal copy of others repository which we can modify without affecting the original project whereas Clone is used to create a local copy of the remote repository. This process helps us to edit and modify files locally.

**2. What are branches in Github?**
A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master. As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically. You can create new branches.

**3. What is PR?**
*Pull requests (PR)* let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.
There are 2 main workflows when dealing with pull requests:
a. PR from a forked repository.
b. PR from a branch within a repository.

**4. Can we delete the master branch. If not, Why?**
*Yes*, we can delete the master branch but we need to follow some steps first:
a.	Go to the GitHub page for your forked repository, and click on the Settings button. Click on the Branches tab on the left hand side. There's a Default branch dropdown list near the top of the screen.
b.	From there, select placeholder (where placeholder is the dummy name for your new default branch). Confirm that you want to change your default branch.
c.	Now, perform git command- git push origin :master in git bash then your master branch will be deleted.

**5. How can we delete a branch?**

In *Git Bash*, write the command git branch –d <Branch Name> and the branch will be deleted.
	OR 
On *Git hub*, navigate to the main page of the repository. Above the list of files check branches.
Scroll to the branch you want to delete, then click on the delete icon.
