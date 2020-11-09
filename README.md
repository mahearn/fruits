# Git and Github - opening session : demonstration workflow

## Description

The purpose of this activity is to demonstrate some of the ways git and github can be used by multiple developers to contribute to a project.

## Walkthrough

### Demonstration of an example workflow in Github

In this step, we'll create a new repo called `Fruits`. It contains a single file called `fruits.md`.

1. Each person clones the repo onto their local drive.
2. The person who does not own the repo but is contributing to it, will:

- create a branch in which to make the changes
- add some fruits to the file
- **commit** the changed file and **push** it up to the remote repo on Github
- go to Github and create a **pull request** (PR) to ask the owner to merge the changes into the master branch

3. The owner will read the pull request and check out the changes, then merge the changes into master
4. To complete the workflow cycle, the owner then goes to the local repo and does a `git pull` to pull down the new changes in the master branch from Github.

### Explanation

Now that each person's local repo contains the same changes that are on Github, the workflow can continue:

- make change
- `git add --all` (adds the changes onto the staging area)
- `git commit -m "Some meaningful message indicating what changes are in this commit" (captures a snapshot of the project's currently staged changes)
- `git push` (pushes or uploads the changes into the corresponding branch on Github)
