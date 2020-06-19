                          Task 1 Questions and Answers

hello guys, I am Anshul Hedau from YCCE nagpur, C.T. 3rd year.
Task 1 Solution-
1) What is Git and github?
 --Git is an open-source distributed version control system that keeps track of software assets and helps run more efficient development processes.
In a distributed version control system (DVCS), the version information is maintained with every copy of the code.
 It allows peer-to-peer sharing.
Git is simple nd powerful with the following pros:
Performance:. Commits, branching and merging is faster in Git than centralized version control systems like CVS, SVN.
Security:The integrity of the code is easier to verify on Git. It uses SHA1 cryptographically secure hashing. The hashes are unique to each modification. If anyone changes a modification, the hashes will not match.
 This property of Git makes it harder for anyone to sneak in code changes surreptitiously.
Flexibility: Git was designed to adapt to any workflow. Older version control systems are more restrictive.
--Github -it is the website that hosts Git repositories online, making it easier for developers to share code.
2) why GitHub is so popular in most of the project ?
--GitHub makes it easy to share code between multiple computers and developers. It's become the centralized organization tool of the open source community and, in turn, is used by thousands of companies and teams.
Some GitHub users have one repo they work with every day, some have hundreds.
3)What is a version control system ? How git is a VCS ?
-- Version control systems are a category of software tools that helps record changes to files by keeping a track of modifications done to the code.
Git also uses the principles of VCS that's why it is a VCS.
4) What are the other platforms similar to GitHub?
-- BitBucket
    GitLab
    Phabricator
    Sourceforge
5) Why are you interested in learning of Git and GitHub ?
-- It's because Git makes it simple to code in a team. Plus it gives other vital benefits of working with a team. We can collaborate with other teams also.


                           Task 2 Questions and Answers

Hello everyone this is Anshul Hedau persuing BE in YCCE in Computer technology.
Following is the link to my GitHub repository:
https://github.com/anshul-hedau10/github_series_NodeJS
Task 2-
1) How git workflow works?
--Git works on four fundamental elements
   1.Workspace-working directory
   2.Index(stage)-project is added and ready to be       commited
   3.Local Repository-it resides in our systems and contains all the files with their commit history
   4.Remote Repository-repository on the server to    which every member will have access
2) What are the different stages of git project as commit,add?
--different stages of git project are modified,staged  and commit.
   1.modified-we can make changes to copy of our project without hampering the orignal code
   2.staged-the files which are added and ready to be commited but not yet commited
   3.commit-the staged files are commited to local repository
3) Is it possible to do a git commit before git add?if no,explain why?
--No,It is not possible because as per git workflow first we have to add file from
working directory to local index and then it can be commited.
4) why is git diff is used?
--git diff is used to track the changes made in the project.
   It compares the commited file with the file in staged area.
5) Can we leave the commit messages as blank?
--Yes,it can be done by using  ( git commit -a --allow-empty-message -m "")

                           Task 3 Questions and Answers

Hi everyone I am Anshul Hedau.
Day 3 Task:
https://github.com/codewayy/github_series/pull/38
https://github.com/codewayy/github_series/pull/36
1) What is meant by the term fork and clone?
--Fork:It means to make a copy of orignal repository in your account.
We can modify the repository without harming the orignal one.
Clone:It means to copy the remote repository to a local repository.
Forking is done on github and cloning is done on git.
2) What are the branches of github?
--Branches are effectively a pointer to a snapshot of our changes.
Each repository can have one or more branches.
The default branch name is master branch.
Once we have made changes in the file we can merged it with the master branch.
3) What is PR?
--PR:it stands for Pull Request.
PR are usually make to the owner of the forked repository so that he can  review the changes and then approve.
4) Can we delete the master branch,if not then why?
--Yes,but before deleting we have to set another branch as a default branch.
5) How can we delete a branch?
--By using command:- git branch -d branchnam