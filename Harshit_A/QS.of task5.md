# Following are Question of Task5.

**How github works**
Github is a *web-based* platform used for version control. *Git simplifies the process of working with other people and makes it easy to collaborate on projects.* Because GitHub is a **repository**, it allows your work to get out in front of the public. Moreover, it is one of the largest coding communities around, so using it can provide wide exposure for your project and for you. The more people you have to review your project, the more attention and use it is likely to attract.Team members can work on files and easily merge their changes in with the master branch of the project. ... **Cloning and Forking** Github Repository.


**What is Cloning?**
The git clone *command* copies an existing **Git repository**. This is sort of like SVN checkout, except the “working copy” is a full-fledged Git repository—it has its own history, manages its own files, and is a completely isolated environment from the original repository.**Cloning a GitHub repository creates a local copy of the remote repo.** This allows you to make all of your edits locally rather than directly in the source files of the origin repo. Here’s how to clone a GitHub repository.

**What is Forking?**
A fork is a **copy of a repository**. Forking a repository allows you to freely experiment with changes without affecting the original project.Creating a *"fork”* is producing a personal copy of someone else's project. 
 
**How to make a PR.**
Once there, click on the Fork button in the top-right corner. This creates a new copy of my demo repo under your GitHub user account with a URL like:

**https://github.com/<YourUserName>/demo**
The copy includes all the code, branches, and commits from the original repo.git clone https://github.com/<YourUserName>/demo
Once the repo is cloned, you need to do two things:

# Create a new branch by issuing the command

**git checkout -b new_branch**
**Create a new remote for the upstream repo with the command:**

git remote add upstream https://github.com/kedark3/demo
In this case, "upstream repo" refers to the original repo you created your fork from.

Now you can make changes to the code. The following code creates a new branch, makes an arbitrary change, and pushes it to new_branch:

**Opening the ISSUES**

On GitHub Enterprise, navigate to the main page of the repository.
Under your repository name, 
click  Issues.
If there are multiple issue types, click Get started next to the type of issue you'd like to open.
Type a title and description for your issue.
A sample issue
When you're finished, click Submit new issue.
