# What is git?
- **git** is a version control system (VSC), give you ability to track files changes, and make amount of people to contribute on those files.and this commonly used for software development, but also can be used to track another files changes.

# What is github?
- **GitHub** is a web-based platform that provides hosting for version control using Git. It is a subsidiary of Microsoft, and it offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features. GitHub is a very popular platform for developers to share and collaborate on projects, and it is also used for hosting open-source projects.

# What is type of (VCS)
- Version control is a system that tracks changes to a file or set of files over time so that you can recall specific versions later. It allows you to revert files back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more.

There are two main types of version control systems: centralized version control systems and distributed version control systems.

1- **A centralized version control system** (CVCS) uses a central server to store all the versions of a project's files. Developers "check out" files from the central server, make changes, and then "check in" the updated files. Examples of CVCS include Subversion and Perforce.

2- **A distributed version control system** (DVCS) allows developers to "clone" an entire repository, including the entire version history of the project. This means that they have a complete local copy of the repository, including all branches and past versions. Developers can work independently and then later merge their changes back into the main repository. Examples of DVCS include Git, Mercurial, and Darcs.


# What is deferent between main branch and master branch?
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


