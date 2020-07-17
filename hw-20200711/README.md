# Assignment 11.07.2020
This assignment is to practice basic git command. In your team, your member will be named `dev1`, `dev2`, `dev3`.

Please follow the instructions below:

## Step 1 - create repo
- Create directory named `Octocat` to store project
- Make the directory to be `working directory`
- Create README.md at the root of `working directory`
- Create the commit with the message `Initial the Octocat project`

## Step 2 - remote repo
- Go to github.com and create repository named `octocat`
- Add the remote repository to your project
- Push your project to the remote repository

## Step 3 - create commit
- `dev1` adds any contents on line no.1. For example, add `Hello, this is Octocat`.
- `dev1` creates the commit with the message `Update README.md #1`
- `dev2` adds any contents on line no.2. For example, add `I'm going to show you how I use git`
- `dev2` creates the commit with the message `Update README.md #2`
- `dev3` adds any contents on line no.3. For example, add `Let's start with git init`
- `dev3` creates the commit with the message `Update README.md #3`
**Remark:** please make sure that you pull the latest document from the remote repository

## Step 4 - branching and merging
- All team mebers require to pull the latest update from the remote repository before starting the next step
- `dev1` creates new branch named `dev1` from `master` branch
- Edit line no.1 with any text
- Create a commit
- Merge `dev1` branch to `master`
- `dev2` creates new branch named `dev2` from `master` branch
- Edit line no.2 with any text
- Create a commit
- Merge `dev2` branch to `master`
- `dev3` creates new branch named `dev3` from `master` branch
- Edit line no.3 with any text
- Create a commit
- Merge `dev3` branch to `master`

## Step 5 - solving merge conflicts
- All team mebers require to pull the latest update from the remote repository before starting the next step
- `dev1` edit line no.1 with any text
- Create a commit and push your update to master branch
- `dev2` creates new branch named `c2`
- Edit line no.1 with any text
- Create a commit
- Switch to `master` branch
- `dev2` pulls the latest update from `master` branch of remote repository
- Merge code from `c2` to `master` branch and fix the conflicts
- `dev3` creates new branch named `c3`
- Edit line no.2 with any text
- Create a commit
- Switch to `master` branch
- `dev3` pulls the latest update from `master` branch of remote repository
- Merge code from `c3` to `master` branch and fix the conflicts

