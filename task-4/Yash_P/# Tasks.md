# Tasks


## Task 1


1. What do u mean by git and github?

Ans-
Git - It's a distributed version control system. Means it's keeps track of the history of the project in the local machine. One of The key features is collaboration. It allows two or more people to work together on the same project at the same time.
Github - It can be considered as a web cider or a kind of service. It provides a bed based graphic interface to perform git taks.


2. Why is GitHub do popular and used in most of the projects?

Ans -
GitHub is an open-source repository hosting service, sort of like a cloud for code. It hosts your source code projects in a variety of different programming languages and keeps track of the various changes made to every iteration.


3. What is version control system? How is git a VCS?

Ans -
VCS - Version Control System is basically a tool that helps to keep track of the changes in the project. It also keeps each team member working on the project at latest version.
Git is a distributed VCS as it allows the user to keep a local repository of the work in their local system. It is responsible for tracking all the changes and history of the project.


4. What are the other platforms similar to GitHub?

Ans -
✓Gitlab
✓launchpad
✓Bitbucket
✓Gitcracken
✓SourceForge
5. Why are u interested in learning of git and github?

Ans -
Git and github provides is interesting in the way of project handling. Also, since I want to learn new things and this is interesting I am curious to know more about it and it's functions...


## Task 2

a)How git workflow works?

Ans - The main idea behind the  Workflow is that all feature development  should take place in a dedicated branch instead of the master branch. This encapsulation makes it easy for various  developers to work on a particular feature without disturbing the main codebase. We have  one central repository. Each developer clones the repository and locally made changes in the code and commit it and then pushes  it to the central repository so that the  other developers can  pull and use in their work.


b)What're the different stages of a git project as commit, add?

Ans - Git Workflow consist of the following:
•	Workspace(also known as Working Directory)
•	Index(also known as Stage)
•	Local Repository(also known as Head)
•	Remote Repository
  git clone is a Git command line utility which is used to target an existing repository and create a clone, or    copy of the target repository.
Add command adds the file from working directory to the index .
Furthur if we need to commit it in local repository we use commit command .
Commit  –a command is used to simply commit and stage at once.
push command is used to push the changes  from local to remote repository.
fetch command is used to get  the file from remote to local repository.
merge command takes changes  from local repository to workspace.
pull command will collect the changes from the remote repository then will be taken into  local repository and further into workspace in one go.


c) Is it possible to do a git commit before git add . if you have made any changes? Explain why?

Ans - No, it is not possible because first we add file to stage and then we undergo commit or save it into local repository.


d) Why is git diff used?

Ans - This command is used to check the difference between the files in the stage and in the workspace.


e) Can we leave the commit message as blank?

Ans - Yes we can do it by using the below command :
git commit -a --allow-empty-message -m ""


## Task 3


Here are the answers to the questions....


1) What is meant by the term fork and clone?

Ans - Forking - a repository allows one to freely experiment with changes without affecting the original project as it is associated with our GitHub account. A fork acts as a remote, server-side copy of a repository, distinct from the original. Forking in git refers to the making of a personal copy of others repo which if we want we can modify without affecting the original project.
Clone - When we create a repo on our GitHub Server, it exists as a remote repository and it can be cloned to create a local copy on our computer and sync between the two locations.


2) what are branches in github?

Ans - The way git, and GitHub, manage this timeline — especially when more than one person is working in the project and making changes — is by using branches. A branch is essentially is a unique set of code changes with a unique name. Each repository can have one or more branches. ... One word: the master branch is deployable.


3) What is PR?

Ans - PR allows others to know about the changes that have been pushed to a github repo. Once a PR is sent other people can review the changes and also discuss the potential modifications. It can even push follow up commits if necessary.
The two type of workflows in PR's are:
~PR from a forked repo.
~PR from a branch within a repo.


4? Can we delete a master branch. If not, why?

Ans - Yes the master branch can be deleted but only when certain steps are followed.
Go to the GitHub page for your forked repository, and click on the Settings button. Click on the Branches tab on the left hand side. There's a Default branch dropdown list near the top of the screen.
From there, select placeholder (where placeholder is the dummy name for your new default branch). Confirm that you want to change your default branch.
Now, perform git command- git push origin :master in git bash then your master branch will be deleted.


5) How can we delete a branch?

Ans - In Git Bash, write the command git branch –d <Branch Name> and the branch will be deleted.
Procedure for deleting in git hub:
On git hub, navigate to the main page of the repository. Above the list of files check branches.
Scroll to the branch you want to delete, then click on the delete icon.