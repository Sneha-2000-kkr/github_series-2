# GitHub Series - Task 5

## How GitHub works :
GitHub is a highly used software which is typically used for **version control**. It is helpful when more than just one person is working on a project. GitHub is a web-based hosting service for git repository to bring team together. It is a graphical interface and a development platform created for millions of developers. It provides a platform as a collaborative effort to bring teams together.
**Working on GitHub :** There is one central repository. Each developer clones the repo, works locally on the code, makes commits, and push it to central repository. Then, a pull request is made asking owner of repo to implement the changes (by merging) made if the owner finds them useful. 
### GIT WORKFLOW

- There is one Central repository. Any developer who wants to make any changes clone that repository and make changes locally using commit command. Then pushes it to the central repository so that any other developer wanting to make any change can pull and use in their work.

#### Fundamental elements of git workflow

Git Workflow consist of the four fundamental elements: 
• **Workspace**(also known as Working Directory) and if we consider a file, it can have 3 states:
    (a)Committed : meaning latest changes in the data is stored in local repo.
    (b)Modified: means the changes are done but are not securely stored or will not be reflected in local repository.
    (c)Staged: meaning file is part of index element.

• **Index**(also known as Stage)
• **Local Repository**(also known as Head)
• **Remote Repository**

## Forking And Cloning :
When you create a repository on GitHub, it exists as a remote repository. You can clone your repository to create a local copy on your computer and sync between the two locations. You can even fork and clone someone’s repository if you are interested in contributing to it, cloning creates a local copy on your computer on which you can make changes and make a pull request later (after adding and committing your changes) requesting the owner to implement the changes made by you. When you fork a repository, you create a copy of the original repository (upstream repository) but the repository remains on your GitHub account. Whereas, when you clone a repository, the repository is copied on to your local machine with the help of Git. Fork in git means making a personal copy of others repository which we can modify without affecting the original project whereas Clone is used to create a local copy of the remote repository. This process helps us to edit and modify files locally.

## Pull Requests :
**Pull requests** let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

## Issues :
**Issues** are a great way to keep track of tasks, enhancements, and bugs for your projects. They’re kind of like email—except they can be shared and discussed with the rest of your team. Most software projects have a bug tracker of some kind. GitHub’s tracker is called Issues, and has its own section in every repository. You can even add a label to and Issue and can also add an assignee (person who is supposed to handle that issue) to it.  
