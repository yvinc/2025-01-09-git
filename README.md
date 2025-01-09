# 2025-01-09-git
DSCI 310

- `git clone`: Does a one-time download from Github to your local computer.
    - Make sure the directory you're cloning into is not already a git repo.
    - **DON'ttt** nest one repository into another repository.
        - The parent folder should not be under version control.
    - Can use `cd ..` and `git status` to check whether the parent folder was already under git version control.

- ;P practice the add-stage-commit cycle!

- git status: tells you what's happening in your current git repo
- git add <file>: adds <file> to the staging already
- git commit -m "...msg": creates a commit (aka a snapeshot) with the changes in the staging area with the message you supplied.