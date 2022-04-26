# Basic Git Commands

Note that this README contains the git commands in sequential order to:

- create a local repository with new files
- add a commit
- push commit history from local repo to a new remote repo on GitHub 

## Adding commit history
1. Create project directory 
    * `mkdir git-intro`
2. Navigate to project directory
    * `cd git-intro`
3.  Initialize Git
    * `git init`
4. Check Git Status
    * `git status`
5. Create a new file
    * `touch README.md`
6. Add to a file
    * `echo Great answer, Yakiv >> README.md`
7. Add untracked and modified files to staging
    * `git add .`

8. Commit files to commit history
    * `git commit -m "Added readme"`

## Remote Operations
9. Create a GitHub repo
    * [Create a new GitHub Repository](https://github.com/new)
10. Connect local repo to a remote repo named origin
    * `git remote add origin git@github.com:nolanknill/git-review.git`
11. Check what remote repos are connected to our local repo
    * `git remote -v`
12. Push commits on local main branch to the remote's main branch
    * `git push -u origin main`