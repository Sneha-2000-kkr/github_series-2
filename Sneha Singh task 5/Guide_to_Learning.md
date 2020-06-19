# GUIDE TOWARDS LEARNING GIT AND GITHUB

This is way to learn to **git and github** from beginning to basic concepts.
Let's start with basic concepts.
There are a ton of ways to use Git and GitHub, but getting started with GitHub doesn’t have to be overwhelming.
You don’t need to be some kind of master coder or anything.
You can even do the most important things right on the GitHub website!

>## Sign Up to **Github** and Installation of **Git Bash**
Go to GitHub and sign up for an account. You could just stop there and GitHub would work just fine.
In order to work on your local computer system you need to install Git Bash.
Now go to your terminal and introduce yourself to Git! 
To set your username for every repository on your computer, using git command ` git config --global user.name "<your_name>" `.
If you want to set your name for just one repository, leave out the word “global" .
Now you can tell Git your email, and make sure it’s the same email you used when you signed up for GitHub,using git command
` git config --global user.email "<your_email_id>" `.
**Now you’re ready to start using Git on your computer!**.
>## Getting Started to work with **Git** and **Github**
Now making a new repository in **github** is every simple ,you just need to go to corner of the window screen and you will see a ` + ` sign and get option for **New Repository**.
else in **Git Bash** To get started, perform a ` git init` to create a new repository from your project directory.
If you have a project directory, just go to your terminal and in your project directory run the command
`git init` If you want to initialize your project with all of the files in your project directory, run
`git init .` to include everything.
Let’s say you have a folder for your project called “new_project.” You could head on over to that folder in your terminal window and add a local repository to it by running
``
cd new_project
git init
``

Now you have a new hidden directory called `.git` in your project directory. This is where Git stores what it needs so that it can track your project. Now you can add files to the staging area one by one with
`git add <filename_one>`
or run
`git add .`
to add all of your files to the staging area. You can commit these changes with the command
`git commit -m "<add a commit message here>"`
and if you’re happy with your changes, you can run
`git push`
to push your changes through. You can check whether or not you have changes to push through any time by running
`git status`
If you made some changes, you can update your files on at a time with
`git add <filename>`
or
`git add --all`
Then commit them with your commit message and push them through.
That’s it! You can now initialize a repository, commit files, commit changes, and push them through to the master branch.
>## Working on other's Repository - **Cloning** and **Forking** 
In order to clone a repository onto your computer, go to the repository on the GitHub website and click the big green button that says **Clone or download.** Now click the clipboard icon to copy and paste it to your clipboard.
To clone the repository, use git command 
`git clone <that_thing_you_just_copied>`.
Now you have a new GitHub repository that you can work with cloned right on your desktop! That command pulled in a complete copy of the repository right to your system where you can work on it, make changes, stage the changes, commit the changes, and then push the changes back to GitHub.
If you ever want to just play with a project on your own, you can fork it on the GitHub website instead of cloning it. Look up near the top right corner of the screen for the “fork” button and click it. This will make a copy of the repository in your repositories for you to play with on your own without doing anything to the original.
> ## Git WorkFlow
Let’s say you have a project going and you maybe have a lot of different ideas and features in mind at any given time. Some features might be ready to go, but some might not. Maybe you’re working with other people who are all kind of doing their own thing. This is where branching comes in!
A branch is a separate space where you can try out new ideas. If you change something on a branch, it doesn’t affect the master branch until you want it to. This means that you can do whatever you want to do on that branch until you decide it’s time to merge it.
The only branch that’s going to permanently change things is the master branch. If you don’t want your changes to deploy immediately, then make your changes on a separate branch and merge them into the master branch when you’re ready.
If you’re working with others and want to make changes on your own, or if you’re working on your own and want to make changes without affecting the master branch, you want a separate branch. You can create a new branch at any time.
It’s also pretty simple to create a branch named “new_feature” in your terminal and switch to it with
`git checkout -b new_feature`
Once you create a branch, you can make changes on that branch. This makes it easy to see what you’ve changed and why you’ve changed it. Every time you commit your changes, you’ll add a message that you can use to describe what you’ve done.

`git checkout`,this git command 
lets you check out a repository that you’re not currently inside of. You can check out the master branch with
`git checkout master`
or look at the “new_feature” branch with
`git checkout new_feature`
When you’re done with a branch, you can merge all of your changes back so that they’re visible to everyone.
`git merge new_feature`
will take all of the changes you made to the “new_feature” branch and add them to the master.
In order to create an upstream branch so that you can push your changes and set the remote branch as upstream, you will push your feature by running
`git push --set-upstream origin new_feature`
After you make some changes and decide you like them, you open a pull request.
**Doing these same stuffs of creating a new branch and merging it to master branch via Github**
You can also create a new branch any time right on the website by going to your repository, clicking the drop-down menu near the left-middle side of your screen that says **Branch: master,** typing a branch name, and selecting the **Create branch** link .
If you’re working on a separate branch, your changes only affect that branch.
If you’re happy with your changes and you want to merge your changes to the master branch, you can open a pull request. 
You can open a pull request as soon as you make a commit, even if you haven’t finished your code. You can do this right on the website if you’re more comfortable with that. If you’ve made some changes on your branch and you want to merge them, you can
- Click the pull request tab near the top center of the screen
- Click the green **New pull request** button
- Go to the **Example Comparisons** box and select the branch you made to compare with the original branch.
- Look over your changes to make sure they’re really what you want to commit.
- Then click the big green **Create pull request** button. Give it a title and write a brief description of your changes. Then click   **Create Pull Request!**
Now if this is your repository, you can merge your pull request by clicking the green **Merge pull request** button to merge the changes into master. Click **Confirm merge**, once its merged it is showed in purple box as **merged**.
 the branch you merged can also be deleted with the **Delete branch** button .
>## Merging Conflicts
Merge conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file
You must resolve this merge conflict with a new commit before you can merge these branches.
- Open Git Bash.
-Navigate into the local Git repository that has the merge conflict.
`cd REPOSITORY-NAME`make necessary changes.
- Add or stage your changes.
` git add .`
- Commit your changes with a comment.
` git commit -m "Resolved merge conflict"`


***These are some basic Concepts you need to get started with Git and Github**
***Thanks for your patient reading:smile:***
