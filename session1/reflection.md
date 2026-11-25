PRACTICAL 1

Q1. Why is a commit history useful when maintaining software?

A commit history is useful because it records the changes made to a software project, including the commit messages and the order of modifications. It helps developers understand how the project has developed and identify when a particular problem or bug may have been introduced. For example, if an error occurs in the README file, I can review my commits, such as Add README for SCM evidence repository and Add student name to README, to identify which change might have caused the issue. This makes troubleshooting and maintaining software easier because previous changes can be inspected.

Q2. Explain the difference between Git and GitHub.

Git is a distributed version control system that tracks changes to files and manages project history on a computer. GitHub is an online platform that hosts Git repositories and provides collaboration features such as pull requests and code reviews. In this practical session, I used Git to manage my local scm-lab-evidence repository and GitHub to publish and share it online. I also completed the GitHub Skills exercise using a separate repository to practise branching, committing, creating pull requests and merging changes.

Q3. What risk does working on a branch and using a pull request reduce?

Working on a separate branch and using a pull request reduces the risk of introducing incomplete or incorrect changes directly into the main branch. It allows developers to review proposed changes before they become part of the main project. For example, in the GitHub Skills exercise, I created the my-first-branch branch and added a PROFILE.md file before submitting a pull request. This workflow helps prevent untested changes from affecting the main version of the software.

Q4. Which commands changed only your computer and which changed GitHub?

Commands such as git init, git add, git commit, git status, git diff, git log, git switch and git merge were used to manage the repository on my computer. The git remote add command configured the connection to my GitHub repository locally, while git clone downloaded a copy of the repository to another folder without changing the original GitHub repository. The git push command uploaded my local commits to GitHub, while git pull downloaded and integrated changes from GitHub into my local repository. Therefore, pushing and pulling allowed me to synchronise changes between my computer and the online repository.


Git Concepts

| No. | Concept | Explanation |
|---|---|---|
| 1 | Repository | A storage location containing project files and their version history. |
| 2 | Working Tree | The directory containing files currently being edited or modified. |
| 3 | Staging Area | An area where changes are prepared before being committed. |
| 4 | Commit | A saved snapshot of changes in the repository's history. |
| 5 | Branch | An independent line of development that allows changes to be made without affecting the main branch. |
| 6 | Merge | The process of combining changes from one branch into another. |
| 7 | Remote | A repository hosted on a server, such as GitHub, for collaboration and synchronisation. |
| 8 | Clone | Creating a local copy of an existing remote repository. |
| 9 | Push | Uploading local commits to a remote repository. |
| 10 | Pull | Retrieving and integrating changes from a remote repository. |

PRACTICAL 2

Q1. Why is a commit history useful when maintaining software?

A commit history is useful because it records the changes made to a project, including the commit messages, authors and sequence of modifications. It helps developers identify when a particular change was introduced and investigate the possible cause of a bug. For example, in my `scm-lab-evidence` repository, I can use `git log` to trace the changes from `Set deployment target to staging` to `Set deployment target to production` and then `Resolve conflict: staging first, production after approval`. This makes it easier to understand previous changes and identify which commit may be related to a problem.

Q2. Explain the difference between Git and GitHub.

Git is a distributed version control system used to track changes in source code and manage different versions of a project locally. GitHub is a cloud-based platform that hosts Git repositories and provides collaboration features such as pull requests and code reviews. For example, I used Git to manage my local `scm-lab-evidence` repository, while GitHub hosted its remote repository. I also used GitHub Skills exercise repositories, such as `skills-review-pull-requests` and `skills-resolve-merge-conflicts`, to practise branching, pull requests and merge conflict resolution.

Q3. What risk does using a branch and pull request instead of changing main directly reduce?

Using a separate branch and pull request reduces the risk of introducing incomplete, incorrect or untested changes directly into the main branch. It allows developers to work independently without affecting the stable version of the project. The pull request also provides an opportunity for other developers to review the changes and identify potential problems before merging. This helps maintain the quality and stability of the main branch.

Q4. Which commands changed only your computer and which changed GitHub?

Commands such as `git add`, `git commit`, `git status`, `git log`, `git diff`, `git branch` and `git switch` mainly affected or displayed information about my local repository. The `git clone` command downloaded a copy of the GitHub repository to my computer, while `git pull` retrieved remote changes and updated my local repository. The `git push` command uploaded my committed changes from my computer to GitHub. Therefore, pushing changes updates the remote repository, while most other commands operate locally or retrieve information from the remote repository.

| Term | Definition |
|---|---|
| Repository | A project folder that contains the files and the complete history of changes tracked by Git. |
| Working tree (working directory) | The current checked-out files and folders in the repository where users make changes. |
| Staging area (index) | An area where selected changes are prepared before they are saved in the next commit. |
| Commit | A saved snapshot of the staged changes in the repository, containing information such as the author, date and commit message. |
| Branch | A movable pointer to a sequence of commits that allows developers to work on different changes independently. |
| Merge | The process of combining changes from one branch into another branch. |
| Remote | A named reference to another Git repository, usually hosted on a server such as GitHub. For example, `origin` refers to the remote repository. |
| Push / Pull / Clone | Push uploads local commits to a remote repository. Pull downloads and integrates changes from a remote repository. Clone creates a local copy of a remote repository, including its commit history. |