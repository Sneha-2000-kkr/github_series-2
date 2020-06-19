# Task 5 of Github Series.

### This guide helps in explaining the working of github and its main concepts.

## What is Git and Github?

- Git-Git is installed and maintained on your local system (rather than in the cloud) and gives you a self-contained record of your ongoing programming versions. It can be used completely exclusive of any cloud-hosting service — you don’t even need internet access, except to download it. Git is responsive, easy to use, and inexpensive. GitHub-GitHub is designed as a Git repository hosting service. GitHub is a for-profit service (although basic repository-hosting features are available at no cost to those who are willing to create a user profile.

## What is Gitbash?

- Git Bash is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience. Bash is an acronym for Bourne Again Shell. A shell is a terminal application used to interface with an operating system through written commands. Bash is a popular default shell on Linux and macOS. Git Bash is a package that installs Bash, some common bash utilities, and Git on a Windows operating system.

## Git Workflow

- The Gitflow Workflow defines a strict branching model designed around the project release. This provides a robust framework for managing larger projects.  Instead of a single master branch, this workflow uses two branches to record the history of the project. The master branch stores the official release history, and the develop branch serves as an integration branch for features. It's also convenient to tag all commits in the master branch with a version number.

## Different stages of a git project

- 1. **Modified**: Git we can create a repository, a repository is basically a kind of a directory that contains all the files related to your code. So, in the repository we can write code, and maintain it. This is called Modification, i.e. making some additions to the original project.
2. **Staged**: Staging area is place prior to the actual implementation of changes, i.e. this area contains all the added files that contain new code, which are ready to be joined to the remote repository.
3. **Commit**: Commit is a set of new files that are being added to a project as part of the modification.

## Git as a version control system(VCS)

- Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. For the examples in this book, you will use software source code as the files being version controlled, though in reality you can do this with nearly any type of file on a computer.
 - There are 3 Version Control Systems :
    1. Local Version Control Systems
    2. Centralized Version Control Systems
    3. Distributed Version Control System

## Making a new Repository and initialising it

* In your Github account click the option NEW repository.

* Then give a repository name and make a README file describing your repository.

* Then open gitbash, to access the repository write the command `<cd repo_name>`.

* Then initialize this repository, by using command : `<git init>`

* Add a file in this repo and to make changes in github add it to your repo using `<git add .>` command

* Then perform git committ use command : `<git commit -m "Message here">`

* Then push it to the repository to make a remote copy of it using command : `<git push -u repo_name master>`.

## Fork and clone in git

- A **fork** is a remote, server-side copy of a repository, distinct from the original. Fork in git means making a personal copy of others repository which we can modify without affecting the orignal project whereas **Clone** is used to create  a local copy of the remote repository.This process helps us to edit and modify files locally.

We can fork any repository by clicking the fork option on the right side of the repository.

For cloning the repository, we need to use git bash and provide the following command:

1. First go the forked repository.

2. Then click clone or download option.

3. Copy the URL.

4. use command `< git clone <Copied Url> >`

## Branches in git

- A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master. As you start making commits, you’re given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically.

### For Making a new branch:

Use command :
`<git branch branch_name>`

To enter into a branch use command :
`<git checkout branchname>`

To see list of all branches in your project use command :
`<git branch -ls>`

To delete a branch, use command :
`<git branch -d branch_name>`

## What is a pull request in github

- Pull requests let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

### How to make a Pull Request(PR)?

1. Fork a repository

2. Enter the forked repository from your account.

3. Make a directory using command `<mkdir>`.

4. Enter the directory using command `<cd directory_name>`.

5. Add some text files in this directory by either physically going to it in your system or by command : `echo "Content" > fileName.txt` or `touch filename.txt`

6. Now use command : `<git add fileNme.txt >`, to add the file.

7. Commit the file: `<git commit -m "Message">` 

8. Now push it to the repository using command : `<git push origin master>`.
  Here if we are doing this by making any other branch, We need to push it by first usng git pull command and then by using `<git push --set-upstream origin branch_name>`.

9. Now go the repository and click Create pull request button.

10. Provide a good name for PR and a good description as well, and then Click option Compare and then see the base and head repository.

11. Click create pull request and your PR will be opened until and unless the head of the repository merges it.

## Merge Conflicts

- A merge conflict is an event that occurs when Git is unable to automatically resolve differences in code between two commits. When all the changes in the code occur on different lines or in different files, Git will successfully merge commits without your help.
However, when there are conflicting changes on the same lines, a “merge conflict” occurs because Git doesn’t know which code to keep and which to discard.

#### Performing merge and checking for conflict

1. Either make a git repository or enter into your git repository using cd command and initialize it using : `<git init>`.

2. Now make a text file names merge.txt and add content to it.

3. Add this by using `<git add merge.txt>`

4. Commit it by using   `<git commit -m "Message">`

5. Now, one file name with content is made in the repository.

6. Now make a new branch and enter into it using command " `<git checkout -b newbranch> .

7. Override the content in merge.txt file.

8. Now add and commit it using : `<git add merge.txt>` and `<git commit -am "Message">`

9. Now enter your master branch using : `<git checkout master>`

10. Now write `<echo "Content to append" >> merge.txt>`

11. commit it

12. Now write :  `<git merge newbranch>`.

### A conflict might occur.

### HOW TO VIEW MERGE CONFLICT

1. Use command : `<git status>` to see the merge conflict.
(b)The  use `<cat merge.txt>` to see the conflict and its cause.

- Many signs like <<<<<<<, >>>>>>> and ======== will appear.
- These are called conflict dividers and we need to erase them to solve the merge conflict.


### SOLVING MERGE CONFLICT

1. To solve the merge conflict, we need to open the text file called merge.txt.
2. After entering the file, we need to delete all the conflict dividers\
3. After deleting it, save the file and write command: `<git commit>` and then push it.

Now your Merge conflict is solved.

### ISSUES IN GIT

Issues are used to track ideas, enhancements, tasks, or bugs for work on GitHub Enterprise. You can collect user feedback, report software bugs, and organize tasks you'd like to accomplish with issues in a repository. Issues can act as more than just a place to report software bugs.


### CREATING ISSUE IN GIT

1. To create an issue, clone a repository or make it in your own repository.
2. Go to the option issue.
3. Give a good name to your issue and a good description to it.
4. We can add labels to it by which we can tell which kind of issue it is.
5. We can also make our own label.
6. Then click Create issue and your issue is created/opened.
7. We can add comments to it and can resolve it.

Hope this article helps you in solving your github doubts.

Regards,

Vatsal Vijaykumar Shah