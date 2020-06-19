# Task 1:
**1. What do you mean by git and GitHub?**

> **Git:**
Git is a free, open-source tool which is used to track changes to source code over a period of time. A Distributed Version Control System, that means every machine will have its own copy of the repository, in which changes to code are stored locally. it is useful in coordinating work among multiple people working on a project. Its style of working as in
Commits, branching and merging is faster than centralized version control systems like CVS, SVN.
The integrity of the code is easier to verify on Git. It uses SHA1 cryptographically secure hashing. The hashes are unique to each modification. If anyone changes a modification, the hashes will not match.
This property of Git makes it harder for anyone to sneak in code changes surreptitiously. That is why people interested to be a contributor, need to grand permission from concerned authorities, make a colon of the code to their system environment and commit changes to their local or server repository.

> **GitHub:**
GitHub is a cloud-based Git repository hosting service. While Git is a command line tool, GitHub provides a web-based graphical interface. It provides various different features that make it easy for a team to work collaboratively on a project.

**2. Why GitHub is so popular and used in most of the projects?**

GitHub is popular because it is a web-based service which provides cloud storage for source code. It has an immensely powerful community and a very large user base thus making it the world's largest software development platform.This is really to understand under this concept that for instance
5 people are working on some project each one is having their fragment of task to be completed. Now ,after they have completed their task they just push their code to company's server's repository. Here it will compile and be saved.
It's very pratical to see not every code is completely correct. They have some bugs
So these projects being open source allows others to contribute to these projects by eradicating bugs, making it more efficient.

**3. What is a version control system? How Git is a VCS?**

 A Version Control System is a Source Code Management tool that records the changes made to a file and helps in maintaining version history, hence enabling recalling of earlier specific versions later on Git is a VCS because it provides  change history of a file and branching and merging features.
Being a open source project, where it welcomes people with their suggestion and contribution. A project might underwent a number of changes with addition of new features or deletion of some old glitches.
This VCS service facilitates them to keep a record of all these versions, editions being performed in these versions.

**4. What are the other platforms similar to GitHub?**

- Source Forge
- Bit Bucket Cloud
- Loud Source Repositories
- Apache Allura
- Git Karken
- Aws Code Commit

**5. Why are you interested in learning of Git and Github?**

 Git simplifies the process of working with other people and makes it easy to collaborate on projects. This allows multiple people to work on the same files at the same time also facilitates one to work on same project with different versions.
Other than domain of computer science
this concept of cloud storage can also be used by non-techies .This will helps me to boost my career and improve my knowledge. I am looking forward to this course in order to be a contributor someday.


# Task 2:


**A. How git workflow works?**

As we know github facilitates many people to team up and and work on  a project in fragments.
The sole concept with workflow is how features are being added to our master branch.

> Basic workflow :
  This contains only one central repository. Each developer clones the repo, works locally on the code, makes a commit with changes, and push it to the central repository for other developers to pull and use in their work.

> Feature Branch :
 Once two developers start working on two separate functionalities within one project,
If one is done with his task and would like to compile the work to see it's working, he will not be able to do so because the other one has not completed his task yet this is where problems begin to appear.This is where branches the core feature of Git come in handy. Branches are independent tracks of developing a project. For each new functionality, a new branch should be created, where the new feature is developed and tested. Once the feature is ready, the branch can be merged to the master branch so it can be release

> Feature Branch and Merge requests :
 The feature branch workflow assumes that all developers on the team have equal knowledge and position. In bigger teams Before a branch is merged to master, it needs to be verified and checked for errors. These can be verified, left with some suitable comments if necessary and if everything is smooth and clear, branches can be merged.

> Gitflow :
This workflow employs two parallel long-running branches:
- Master
- Develop

Master is always ready to be released on LIVE, with everything fully tested and approved.
Develop is the branch to which all
feature branches are merged and where all tests are performed. Only when everything’s been thoroughly checked and fixed it can be merged to the Master.

 **B. What're the different stages of a git project as commit, add?**

To understand different stages of a git project we can see a instance if a team of 5 people are working on a project, they discovered some new feature and  wanted to add them to original software, this can be done and will be appreciated if they don't fell in mess.
In case they do, and wanted to get back to their stable software they can do so.
Git provides a feature of so called undo function to it's project like a undo function works only when it's under time duration of task completion but git provides relaxation by boundless time limit to modify software as and when required.
Every project under the distributed version control system Git, goes through three stages :
- Modified
- Staged 
- Committed.

### Modified:
This simply facilitate team members to make modifications in their local repository without hampering original software.
### Staged:
Now that we have made some modifications to software in our local repository, we want to apply them this is done by git command
` git add.  ` this will keep track of the new files been added and modified. In case we don't add the file and go with git command
` git status `, it will show us files and modification present in our project repository but not added and git will not keep track of these modifications.
### Commit:
This is the final stage, as this stage finally applies the new changes to the remote repository.
So, a commit is a set of new files that are being added to a project as part of the modification. Each commit represents the changes made to project in the past, with the details about the time at which commit was made and the author of the code. So, finally when you make a commit, and it gets committed, then this simply means that you have successfully applied a certain modification to the code.
 

**C. Is it possible to do git commit before git add. If you have made any changes? Explain why ?**

Yes, it is possible to make commit before add using the `git commit -a " commit comment" ` command adds a change in the working directory to the staging area. It tells Git that we want to include updates to a particular file in the next commit. However, git add doesn't really affect the repository in any significant way, changes are not actually recorded until the git commit command is executed. So, whether we use commit before add or after add it will not affect the local repo.

**D. Why is git diff used?**

This command is used to display the differences in the files by comparing the files line by line.

**E. Can we leave the commit message as blank?**

Yes, we can leave the commit message blank. Though it is advised to write comments in our commit message so that we get to know when, by whom and what changes were made in the software.
In order to know this git command   
`git log --author="name of the author whose commit is to be traced"`.
This will display day, date, time, author's name and commit message.

# Task 3

Link to PR via master branch:
https://github.com/codewayy/github_series/pull/25

Link to PR via other branch made :
https://github.com/codewayy/github_series/pull/31

**1) What is meant by the term fork and clone?**

Forking is done on the GitHub Account while Cloning is done using Git. When you fork a repository, you create a copy of the original repository (upstream repository) but the repository remains on your GitHub account. Whereas, when you clone a repository, the repository is copied on to your local machine with the help of Git.
Changes made to the forked repository can be merged with the original repository via a pull request. Pull request knocks the repository owner and tell that “I have made some changes, please merge these changes to your repository if you like it”. On the other hand, changes made on the local machine (cloned repository) can be pushed to the upstream repository directly. For this, the
user must have the write access for the repository otherwise this is not possible. If the user does not have the write access, the only way to go is through the forked request. So in that case, the changes made in the cloned repository are first pushed to the forked repository and then a pull request is created. It is a better option to fork before clone if the user is not declared as a contributor and it is a third party repository (not of the organization).
Forking is a concept while cloning is a process. Forking is just containing a separate copy of the repository and there is no command involved. Cloning is done through the command `git clone` and it is a process of receiving all the code files to the local machine.

**2)  What is branches in github?**

A branch facilitates new set of features to be added to our existing stable code without affecting it . Each repository can have one or more branches. The master branch is deployable.


**3) What is PR?**

PR stands for pull request, Changes made to the forked repository can be merged with the original repository via a pull request. Allows others to know about the changes that have been pushed to a github repo. Once a PR is sent other people can review the changes and also discuss the potential modifications. It can even push follow up commits if necessary.
The two type of workflows in PR's are:
- PR from a forked repo.
- PR from a branch within a repo.

**4) Can we delete a master branch. If not, why?**

Yes the master branch can be deleted .

**5) How can we delete a branch?**

In ***Git Bash***, write the command `git branch –d <Branch Name>` and the branch will be deleted.

Procedure for deleting in ***Git hub***:
On git hub, navigate to the main page of the repository. Above the list of files check branches.
Scroll to the branch you want to delete, then click on the delete icon. 
