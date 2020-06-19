					###Day 3 solution 

**a. What is meant by the term fork and clone?**/soutions

Fork means taking a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.
Cloning a git repository means that you create a local copy of the code provided by the developer. 

**b. What are branches in Github?**/solutions

Especially when more than one person is working in the project and making changes — is by using branches. A branch essentially is a unique set of code changes with a unique name. Each repository can have one or more branches.
	
**c. What is PR?**/solutions

 Pull requests let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

**d. Can we delete the master branch if not Why?**/solutions

	Yes ,we can You need to go to the GitHub page for your forked repository, and click on the Settings button.
Click on the "Branches" tab on the left hand side. There’s a “Default branch” dropdown list near the top of the screen.
From there, select placeholder (where placeholder is the dummy name for your new default branch).
Confirm that you want to change your default branch.
Now you can do (from the command line):


**e. How can we delete a branch?**/solutions

Deleting  a branch locally is by : git branch -d <branch>.




	                       ###Day 2 solution

**A. How git workflow works?**/solutions

Basic workflow :
The idea is simple: there is one central repository. Each developer clones the repo, works locally on the code, makes a commit with changes, and push it to the central repository for other developers to pull and use in their work.

Feature Branch
Once two developers start working on two separate functionalities within one project, problems begin to appear.This is where branches the core feature of Git come in handy. Branches are independent tracks of developing a project. For each new functionality, a new branch should be created, where the new feature is developed and tested. Once the feature is ready, the branch can be merged to the master branch so it can be release

Feature Branch and Merge requests
The feature branch workflow assumes that all developers on the team have equal knowledge and position. In bigger teamsBefore a branch is merged to master, it needs to be verified and checked for errors. Junior developers can create a merge request and assign it to one of the Seniors, so they can review the code and leave comments. If everything’s okay, the request is accepted and the branch is merged.

Gitflow
This workflow employs two parallel long-running branches:
Master
Develop
Master is always ready to be released on LIVE, with everything fully tested and approved.
Develop is the branch to which all feature branches are merged and where all tests are performed. Only when everything’s been thoroughly checked and fixed it can be merged to the Master.

 **b. What're the different stages of a git project as commit, add?**/solutions
 
After adding our changes to the file and running a git status command we can see what are the changes made to the file .The final stage is to commit the change we have made. We do this by recording a short message that explains what we did and why. This human readable explanation will go alongside Git's own record of the change and the file structure snapshot at that point.Once your commit message has been saved and you are back at your git command prompt, you will see a summary of the changes git has made. Running git status again will tell you that your working directory is clean.
c..Is it possible to do git commit before git add. If you have made any changes? Explain why ?
	No its not possible to do git commit before git add .because only after making changes to the file we will add them and to record them we make a git commit that these and these are the changes made to tis file.

**D.Why is git diff used?**/solutions

This command is used to display the differences in the files by comparing the files line by line.

**E. Can we leave the commit message as blank?**/solutions

	Meaningful commit message is part of good development practice and good repository organizing.
 day 1 answer
		
		                ###Day 1 solutions

**1.what do you mean by git and github ?**/solutions
	Git is a version control system that lets you manage and keep track of your source code history . Git is installed and maintained on your local system and gives you a  record of your ongoing programming versions; you don’t even need internet access, except to download it. Git is responsive, easy to use, and inexpensive free, actually.One thing that really keeps Git apart is its branching model. Branching allows you to create independent local branches in your code. This means you can try out new ideas, set aside branches for production work, jump back to earlier branches, and easily delete, merge, and recall branches at the click of a button.

	Github is a  cloud based hosting service that lets you manage git repositories.It’s an online database that allows you to keep track of and share your Git version control projects outside of your local computer/server. And because GitHub is cloud-based, an individual’s Git repositories can be remotely accessed by any authorized person, from any computer, anywhere in the world. Through GitHub, you can share your code with others, giving them the power to make revisions or edits on your various Git branches. This makes it possible for entire teams to coordinate together on single projects in real-time. As changes are introduced, new branches are created, allowing the team to continue to revise the code without overwriting each other’s work. These branches are like copies, and changes made on them do not reflect in the main directories on other users’ machines unless users choose to push/pull the changes to incorporate them. There is also a GitHub desktop application available, which offers some additional functionality


**2.why is github popular and used in most of the projects?**/solutions
	
	Github is a  cloud based hosting service that lets you manage git repositories.It’s an online database that allows you to keep track of and share your Git version control projects outside of your local computer/server. And because GitHub is cloud-based, an individual’s Git repositories can be remotely accessed by any authorized person, from any computer, anywhere in the world. Through GitHub, you can share your code with others, giving them the power to make revisions or edits on your various Git branches. This makes it possible for entire teams to coordinate together on single projects in real-time. As changes are introduced, new branches are created, allowing the team to continue to revise the code without overwriting each other’s work. These branches are like copies, and changes made on them do not reflect in the main directories on other users’ machines unless users choose to push/pull the changes to incorporate them. There is also a GitHub desktop application available, which offers some additional functionality

**3.what is the version control system ? Why is GIT a vcs?**/solutions
	
	Git is a VCS — Version Control System. What that really means is, Git helps us manage our project files. One of the primary things that git does and also the primary reason it exists is to keep track of the entire history of things that you are working on.
This is especially helpful for software developers because when you are working on a project you first build a basic version of it and then try to improve it by adding new features (or) just experiment with things. This whole process of experimenting with new features is incredibly error prone and you might wanna revert back to your original code.This is where Version Control comes into play, it automatically tracks every minute change in your project and allows us to revert back to a previous version no matter how many times you changed your files.
Another awesome thing that Git allows to do is, it allows people to work together on the same project at the same time without disturbing each other’s files. Collaboration is all the more easier with Git.Team members can work on different features and easily merge changes.


**4.what are other platforms similar to github ?**/solutions
	
1.Bitbucket
2.Sourceforge
3.Launchpad
4.Gitlab

**5.why are you interested in learning git ?**/solutions

	I want to learn git and github because I would like to work with other people and  learning git and github makes it easy to collaborate on projects.


























