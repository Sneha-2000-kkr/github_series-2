# GIT
-----------------
It is a open source licensed, version control system(a system that records changes to a file or set of files over time so that we can recall specific versions later), that helps in managing and keeping track of the source code history.It is installed locally on the user's computer.  
Version control system is a software tool that helps a software team manage changes to source code.It keeps track of every modification to the code in a special kind of database.If a mistake is made, developers can turn back to the previous versions and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.  
Git is a version control system as it helps in managing and keeping track of the source code history.Also, it allows developers to work on the same project at the same time without any disturbances.

# GITHUB
-----------
GitHub is a cloud-based hosting service which is built around the Git tool and helps in managing Git repositories.
GitHub is the world’s largest software development platform. It provides cloud storage for source code and supports all popular programming languages.  
It is the largest shared repository with easy version control, secure cloud storage and a large repository for code review automation, continuous integration, code performance and error monitoring and task management.  
Other than github there are sevral platforms present those are:
- Bitbucket
- Source Forge
- Launchpad
- Gitlab
- AWS CodeCommit


### TERMINOLOGIES
------------------
-**Repository** : Git repository is a kind of a directory that stores all the files, folders, and content needed for your project. It is the object database of the project, storing everything from the files themselves, to the versions of those files, commits, deletions, etc. They are not limited by user, and can be shared and copied.

-**Commit** :  Aa commit is like saving an updated file to its original folder and overwrites an older version.

-**Branch** : Branches in github can be defined as the individual projects within a git repository.Different branches within a repository can have completely different files and folders.

-**Checkout** : This is used to switch between branches present in a repository.

-**Master** : The primary branch of all repositories. All committed and accepted changes should be on the master branch. You can work directly from the master branch, or create other branches.

-**Merge** : Taking the changes from one branch and adding them into another (traditionally master) branch.

-**Origin** : The conventional name for the primary version of a repository. Git also uses origin as a system alias for pushing and fetching data to and from the primary branch. For example, git push origin master, when run on a remote, will push the changes to the master branch of the primary repository database.

-**Fork** : To fork means to take a copy of the project, rename it, and start a new project and community around the copy.

-**Clone** : To clone means to create a copy of the forked projects into our local machine.Can be done with the help of "git clone".

-**Pull Request(PR)** : It lets us to tellothers aboutr the changes we've pushed to a GitHub repository.Once a pull request is sent, interested parties can review the set of chnages, discuss potential modifications, and even push follow-up commits if necessary.

-**Push** : Updates a remote branch with the commits made to the current branch. Tha changes are being pushed onto the remote.

-**Issues** : Issues are a great way to keep track of tasks, enhancements, and bugs for the projects. 


### GIT WORKFLOW
----------------
The four fundamental elements in the GIT workflow are:
- Workspace-It is our local directory
- Index(stage)-After creating our files, when we add them they are stored in index or the tagged files to be considered in the next commit
- Local Repository- It is the repository present locally in our computer which conatins the history of thw work we have done and it contains files which are committed
- Remote Repository- It is the repository which is accessible to everyone, whoever have access to it(present in a server)
The three states of the files are:
- Committed-Committed files or latest changes to the files are stored in local repository.
- Modified- Modified files or the changes made to the files are not stored and saved in the lical repository.
- Staged- The changes made to the files or the modified files are stored in index and they are tagged to be considered in the next committ.
In a Git workflow:
- workspace --> remote repository (pushing files or changes to the files in the remote repository from our local directory)
	- The new files or the modified files are stored in workspace, in our local directory.
	- The files are further added to index, so that they could be considered in the next commit using the add command.
	- The staged files are further committed using the commit command to the local repository, so that the changes are stored.
	- To take the changes to the remote repository we use the push command.And the changes made are visible to everyone, having access to the remote repository.
- remote repository --> workspace (fetching files from the repository to our local directory)
	- Files from the remote repo can be brought to the local repo using the fetch command. These files will not be visible in the local directory.
	- to make the files visible in the local directory merge command is used to get the files from the local repo.


### HOW TO USE GITHUB
-------------------
- Initialisig the git repository : <git init>

- Saving the changes made to the project : <git add .>

- To keep track of the changes we need to commit the changes : <git commit -m "Message">

- Viewing the status of the project whether it is a modified or not : <git status>,<git diff>

- Setting up the connection between git repo locally and github : <git remote add origin "URL">

- pushing the files from local computer to github : <git push -u -f origin master>

- After forking the code from one repo we need to clone that into our local computer using the commands : <git clone "URL">

- If we want to create a new branch : <git branch "branch_name">, <git checkout -b alpha>

- For the list of branches : <git branch --list>

- For moving to a particular branch : git checkout "branch_name"

- If we want to push a new branch : <git push --set-upstream origin new_branch_name>\]

