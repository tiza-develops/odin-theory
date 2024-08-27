1. How do you create a new repository on GitHub?
> There are multiple options:
> Perhaps the simplest one is to type in the `new repository` button and clone the empty repo locally
> You can also create a repo locally and adding github as a remote
2. How do you copy a repository onto your local machine from GitHub?
> By typing `git clone <repo-url>.git`
3. What is the default name of your remote connection?
> Origin
4. Explain what origin is in git push origin main.
> The remote location of the main branch
5. Explain what main is in git push origin main.
> The branch to which the changes are published
6. Explain the two-stage system that Git uses to save files.
> 1. Adding files to stage
> 2. Stage files
7. How do you check the status of your current repository?
> To check if your local repository is in sync with the remote one, `git fetch origin`
> To just see the repository, `git checkout origin main`
8. How do you add files to the staging area in Git?
> `git add <files to be staged>`
9. How do you commit the files in the staging area and add a descriptive message?
> `git commit -m "message"`
10. How do you push your changes to your repository on GitHub?
> `git push <remote> <branch>`
11. How do you look at the history of your previous commits?
> `git log`
