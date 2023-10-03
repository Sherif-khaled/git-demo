# What is git?
- **git** is a version control system (VSC), give you ability to track files changes, and make amount of people to contribute on those files.and this commonly used for software development, but also can be used to track another files changes.

#  Why is It So Important?
- Two main advantages of using Git at software development:
1- Tracking the changes and updates. We are able to see who made which changes. Git also provides when and why a change was made.
2- Allowing to work collaboratively. Software development projects usually require many people to work together. Git provides the developers with a systematic way of doing that. Thus, the developers focus on the project instead of extensive communication sessions between the other developers.

# What is difference between local & remote repository? How to connect local to remote?

- **Local repository**
A local repository is a copy of the entire project’s history and codebase that resides on a developer’s machine. When a developer initializes a local repository, Git sets up the necessary infrastructure to track changes, branches, and commits within the project.
- **Remote repository**
A remote repository, as the name suggests, is a repository hosted on a remote server or a code hosting platform like GitHub, GitLab, or Bitbucket. Remote repositories serve as a central hub where developers can collaborate and share their work with others. When working with a remote repository, developers can push their local commits to the remote server and pull the latest changes made by other team members.


# What is github?
- **GitHub** is a web-based platform that provides hosting for version control using Git. It is a subsidiary of Microsoft, and it offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features. GitHub is a very popular platform for developers to share and collaborate on projects, and it is also used for hosting open-source projects.

# What is type of (VCS)
- Version control is a system that tracks changes to a file or set of files over time so that you can recall specific versions later. It allows you to revert files back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more.

There are two main types of version control systems: centralized version control systems and distributed version control systems.

1- **A centralized version control system** (CVCS) uses a central server to store all the versions of a project's files. Developers "check out" files from the central server, make changes, and then "check in" the updated files. Examples of CVCS include Subversion and Perforce.

2- **A distributed version control system** (DVCS) allows developers to "clone" an entire repository, including the entire version history of the project. This means that they have a complete local copy of the repository, including all branches and past versions. Developers can work independently and then later merge their changes back into the main repository. Examples of DVCS include Git, Mercurial, and Darcs.


# What is deferent between main branch and master branch?

- The computer industry's use of the terms master and slave caught everyone's attention in the summer of 2020. Amid the many protests and the growing social unrest, these harmful and antiquated terms were no longer considered appropriate.

**"Both Conservancy and the Git project are aware that the initial branch name, 'master,' is offensive to some people and we empathize with those hurt by the use of that term,"** said the Software Freedom Conservancy.
- 
# Git basic commands

```console
git init

```- this command to create and init new repo

git add <new_file>
- this command to stage untracked files

git commit -m "commit message"
- this command to 

git status

git restore --staged <file>

git branch

git remote add origin <repo_url>

git push --set-upstream origin "branch_name"

git log

git checkout -b "new_branch_name"

git checkout "branch_name"

- rename branch on local repo
git branch -m "old_branch_name "new_branch_name"

- push renamed branch
git push -u "old_branch_name "new_branch_name"

- change pointing HEAD to new branch name
git remote set-head "old_branch_name "new_branch_name"

- get current HEAD
git branch -a

-delete the branch from remote repo
git push origin --delete <branch_name>







