# demo
Wanted to check out the Git and GitHub ans specially the concept of versioning, colabing and co-working!

## Subheader
It is going well!!!!!

### Intro to commands
> "git clone" brings a repository that is hosted somewhere else i.e. Github into a folder on your local machine.
 "add" Track your files and changes in Git.
 "commit" saves your files in Git.
 "push" upload Git commits to a remote repo, like GitHub.
 "pull" ´download changes from remote repo to your local machine, the opposite of push.
 "ls -la" is the equalent of "la" in windows., which means list all.
 "git add ." will add new changes and even new folders will be added to git. For saving changes individually we can use command "git add filename".
> "reset" is used to clear all code and commands in the terminal.


### How to push to GitHub
> First of all check status by using command: ""git status"", the changes will be shown in red higlighted text.
 Then to save locally the changes first use command: ""git  add ."", and check the git status again , now the modifications will bw shown in green highlighted text.
 And now the changes are ready to be commited, which we will do by using command: "" git commit -m "a" -m "a" "", "a" are for your messages, that what and why?.
 Now use command:  ""git push origin main"".
 If this don't works, use first: ""git pull"".
 Then use: ""git log"", to resolve merging issues.
> Then again use: ""git push -u origin main -f"".


### Review workflow through Youtube Video!
> onwards timeline 30:22, there is  review workflow which we learnt in last half hour.
There is also a comparison between GitHub workflow and Local Git Workflow.
For the quick understanding watching the video, whose links is in the following:
> https://youtu.be/RGOj5yH7evk?si=C7-RFK07ULfLap9F&t=1820


 ### Git Branching Overview
>**Definition**: Git branching allows multiple lines of development within a Git repository. It enables developers to work on different features, bug fixes, or experiments simultaneously without affecting the main codebase.
   **Key Benefits**:
    Isolates **features** and **bug fixes**.
    Facilitates **collaborative** work.
    Simplifies **context switching**.
    Enables **parallel development**.
  **Main Branches**:
    **master/main**: The primary branch where the production-ready code lives.
    **feature branches**: Created for specific features, usually merged back into the main branch after completion.
    **hotfix branches**: Used for urgent bug fixes in production.
    **develop branch**: Often used in workflows like GitFlow for ongoing development.
  **Commands**:
    `git branch <branch-name>`: Create a new branch.
    `git checkout <branch-name>`: Switch to a branch.
    `git merge <branch-name>`: Merge a branch into the current branch.
    `git branch -d <branch-name>`: Delete a branch.
  **Best Practices**:
    Use descriptive branch names (e.g., `feature/login`, `bugfix/issue-123`).
    Regularly pull updates from the main branch to avoid conflicts.
    Merge frequently to keep branches up to date.
  **Common Workflows**:
   **GitFlow**: A structured approach with separate branches for features, releases, and hotfixes.
   **Feature Branching**: Create a branch for each feature or task, merge back when done.
>  **Trunk-based Development**: Developers work on short-lived branches, merging changes into the main branch quickly.

### Other commands
- press "q" to exit, when you stuck in terminal.
- you can auto complete the branch name by inputing last characters and simultaniously pressing escape.
- command "git diff" shows you the difference between branches.


