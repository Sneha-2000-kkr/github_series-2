 # Task -1
**1.What do you mean by git and GitHub?**/Answer

Git:
 Git is a free, open-source tool which is used to track changes to source code over a period of time. A Distributed Version Control System, that means every machine will have its own copy of the repository, in which changes to code are stored locally. it is useful in coordinating work among multiple people working on a project
GitHub:
 GitHub is a cloud-based Git repository hosting service. While Git is a command line tool, GitHub provides a web-based graphical interface. It provides various different features that make it easy for a team to work collaboratively on a project.
 
**2. Why GitHub is so popular and used in most of the projects?**/Answer

 GitHub is popular because it is a web-based service which provides cloud storage for source code. It has an immensely powerful community and a very large user base thus making it the world's largest software development platform.
 
**3. What is a version control system? How Git is a VCS?**/Answer

         A Version Control System is a Source Code Management tool that records the changes made to a file and helps in maintaining version history, hence enabling recalling of earlier specific versions later on Git is a VCS because it provides  change history of a file and branching and merging features.
**4. What are the other platforms similar to GitHub?**/Answer

                      I.        Source Forge
                     II.        Bit Bucket Cloud
                   III.        Loud Source Repositories
                  IV.        Apache Allura
                    V.        Git Karken
                  VI.        Aws Code Commit
**5. Why are you interested in learning of Git and Github?**/Answer

           Git simplifies the process of working with other people and makes it easy to collaborate on projects. This allows multiple people to work on the same files at the same time. This helps me to boost my career and improve my knowledge.
	
	
	
## Task -2

https://github.com/Gaushik-007/git_tutorials

**1.How git work flow works?**/Answer

 	   The idea of git work flow is simple. There is one central repository. Each developer clones the repo, work locally on the code, make commits with the changes, and push it to central repository. In simple we can say from workspace to index, index to local repository, local repository to remote repository.
**2.what are the different stages of a git project as commit, add?**/Answer

    	Commit add the file to workplace to the index. Minus u is a syntax that is needed. When we give command to execute git, it commit all the files from index to local repository. By giving commit it is already a part of repository.
**3.Is it possible to do git commit before git add. If you have made any changes? Explain why?**/Answer

   	No, because first of we have to do git add to save the changes and then git commit. Till now I have not made such changes.
**4. Why is git diff used?**/Answer

   	Diff command is used in git to track the difference between the changes made on a file. Since Git is a version control system, tracking changes are something very vital to it. Diff command takes two inputs and reflects the differences between them. It is not necessary that these inputs are files only.
**5. Can we leave the commit message as blank?**/Answer

   	Git generally requires a non-empty message because providing a meaningful commit message is part of good development practice and good repository stewardship.
             
### TASK-3

Pull request 1: https://github.com/codewayy/github_series/pull/23

Pull request 2: https://github.com/codewayy/github_series/pull/30

**a. What  is meant by the term fork and clone?**/Answer

Fork:
A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.
Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.
Propose changes to someone else's project
Clone:
Cloning basically means you want to get a local copy of the code present in the repository.
After cloning you can then do whatever changes you like in the code and then you can pull the changes back to the repository.

**b. What are branches in Github?**/Answer

There is no such thing as branches in Github, it's Git that has branches.
Github is just a tool on top of Git with some additional features and acts as a remote location for your local git repositories.
A branch in Github would essentially mean a branch that was created in Git by someone and pushed to remote(Github).
**c. What is PR?**/Answer

Pull Request (PR) is a Github feature that allows users to collaborate better together.
Usually in source control software there is a main branch that describes production — in git it is the master branch.

**d. Can we delete the master branch if not Why?**/Answer

Yes we can delete master branch by following certain steps
You need to change your GitHub repo default branch.
You need to go to the GitHub page for your forked repository, and click on the “Settings” button.
Confirm that you want to change your default branch.

**e. How can we delete a branch? (Explore a bit about this yourself)**/Answer

To delete the local branch: $ git branch -d branch name
To delete the remote branch: $ git push remote name --delete branch name




