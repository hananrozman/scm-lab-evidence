Q1. Why is a commit history useful when maintaining software?

A commit history is useful because it records the changes made to a software project, including the commit messages and the order of modifications. It helps developers understand how the project has developed and identify when a particular problem or bug may have been introduced. For example, if an error occurs in the README file, I can review my commits, such as Add README for SCM evidence repository and Add student name to README, to identify which change might have caused the issue. This makes troubleshooting and maintaining software easier because previous changes can be inspected.

Q2. Explain the difference between Git and GitHub.

Git is a distributed version control system that tracks changes to files and manages project history on a computer. GitHub is an online platform that hosts Git repositories and provides collaboration features such as pull requests and code reviews. In this practical session, I used Git to manage my local scm-lab-evidence repository and GitHub to publish and share it online. I also completed the GitHub Skills exercise using a separate repository to practise branching, committing, creating pull requests and merging changes.

Q3. What risk does working on a branch and using a pull request reduce?

Working on a separate branch and using a pull request reduces the risk of introducing incomplete or incorrect changes directly into the main branch. It allows developers to review proposed changes before they become part of the main project. For example, in the GitHub Skills exercise, I created the my-first-branch branch and added a PROFILE.md file before submitting a pull request. This workflow helps prevent untested changes from affecting the main version of the software.

Q4. Which commands changed only your computer and which changed GitHub?

Commands such as git init, git add, git commit, git status, git diff, git log, git switch and git merge were used to manage the repository on my computer. The git remote add command configured the connection to my GitHub repository locally, while git clone downloaded a copy of the repository to another folder without changing the original GitHub repository. The git push command uploaded my local commits to GitHub, while git pull downloaded and integrated changes from GitHub into my local repository. Therefore, pushing and pulling allowed me to synchronise changes between my computer and the online repository.

Repository
A storage location that contains project files and their version history, including commits and branches.

Working Tree (Working Directory)
The directory containing the checked-out project files where a developer makes and edits changes.

Staging Area (Index)
An area where selected changes are prepared before they are included in the next commit.

Commit
A recorded snapshot of the staged changes in the repository, identified by a unique hash and accompanied by a commit message.

Branch
An independent line of development that allows developers to work on changes without directly modifying another branch.

Merge
The process of combining changes from one branch into another branch.

Remote
A reference to another repository, usually hosted on a platform such as GitHub, that allows repositories to exchange changes.

Clone
Creates a local copy of an existing remote repository, including its files and version history.

Push
Uploads local commits to a remote repository.

Pull
Fetches changes from a remote repository and integrates them into the current local branch.