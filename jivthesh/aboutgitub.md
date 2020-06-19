**1.what do you mean by git and github ?**/answers

	Git is a version control system that lets you manage and keep track of your source code history . Git is installed and maintained on your local system and gives you a  record of your ongoing programming versions; you don’t even need internet access, except to download it. Git is responsive, easy to use, and inexpensive free, actually.One thing that really keeps Git apart is its branching model. Branching allows you to create independent local branches in your code. This means you can try out new ideas, set aside branches for production work, jump back to earlier branches, and easily delete, merge, and recall branches at the click of a button.

	Github is a  cloud based hosting service that lets you manage git repositories.It’s an online database that allows you to keep track of and share your Git version control projects outside of your local computer/server. And because GitHub is cloud-based, an individual’s Git repositories can be remotely accessed by any authorized person, from any computer, anywhere in the world. Through GitHub, you can share your code with others, giving them the power to make revisions or edits on your various Git branches. This makes it possible for entire teams to coordinate together on single projects in real-time. As changes are introduced, new branches are created, allowing the team to continue to revise the code without overwriting each other’s work. These branches are like copies, and changes made on them do not reflect in the main directories on other users’ machines unless users choose to push/pull the changes to incorporate them. There is also a GitHub desktop application available, which offers some additional functionality

**2.How Git works?***

	The main principle of Git, once you understand it, is astonishingly simple.First, Git handles content in snapshots, one for each commit, and knows how to apply or roll back the change sets between two snapshots. This is an important concept. In my opinion, understanding the concept of applying and rolling back change sets makes Git much easier to understand and work with.

**3.Working with Git?**

	To start working with Git, you just need to run the git init command. It turns the current directory into the Git working directory and creates the repository in the .git (hidden) directory it creates there. You can then start working with Git. The checkout and commit commands are similar to the other source code repositories, but the focus on change sets is the reason why in Git you have the add command . With this command, a change in the working directory is added to the staging area for the next commit.git status helps you keep track of which changes have been added, or not, on what branch you are on.
	
	**git init** — initializes a repository.
	
	**git checkout** — checks out a branch from repository into the working directory.
	
	**git add** — adds a change in a file to a change set.
	
	**git commit** — commits a change set from the working directory into the repository.
	
	**git branch** — creates a new branch from the current HEAD ie) the working directory
	
	**git checkout -b** — creates a new branch from the current HEAD, and switches the working directory to the new branch.
	

	**git diff** – — shows the difference of between the working directory and the given branch.

	**git checkout** – — checks out files from the given branch into the working directory.

	**git merge**— merges the given branch into the current branch.

	**git merge -abort**— aborts a merge that resulted in conflicts.

**Lets see this in detail **

**Q]How to fork a repo?** 

	A fork is a copy of a repository. Forking a repository allows to freely experiment with changes without affecting the original project.
	
**Q]how to clone a repo?**

		when you open a github repo On the right side of the screen, below the “Contributors” tab, you’ll see a green button that says “Clone or Download.” Go ahead and click that. In the window that appears, select the “Clipboard” icon to copy the repo URL to your clipboard.Next, open the Command Prompt (on Windows) or whichever terminal you happen to be using on your computer.In the terminal, navigate to the location in which you would like to store the repo. You can do so by typing the following command:
		$ cd <directory>
		Now, with the repo URL still copied to your clipboard, it’s time to clone the repo. Enter the following command:
		$ git clone <repo-url>
		
**Q]how to make a pull request?**

	Before making a pull request on Github, you will need to create your own branch off the master branch and make sure it is up to date. After that you are free to make and commit changes without affecting the main branch. Once a commit is made, you can create the Pull Request on GitHub, then merge your changes back into the main branch. You can use both the Git command line as well as the Github web interface to perform much of this process.
	
**How to create a isue?**		
	
	On GitHub, navigate to the main page of the repository.Under your repository name, click **Issues.**If there are multiple issue types, click Get started next to the type of issue you'd like to open.Optionally, click Open a blank issue. if the type of issue you'd like to open isn't included in the available options.Type a title and description for your issue.If you're a project maintainer, you can assign the issue to someone, add it to a project board, associate it with a milestone, or apply a label.When you're finished, click Submit new issue.





