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
Now making a new repository in **github** is every simple ,you just need to go to corner of the window screen and you will see a ` **+** ` sign and get option for **New Repository**.
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

