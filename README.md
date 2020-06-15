# Novice Developer's Guide for Contributing to Github Projects

#### 1. Clone _develop_ branch to local system

> syntax: git clone [url] -b [branch-name] --single-branch

```sh
$ git clone git@github.com:SanjeevKumarPandey/novice_developer-s_guide_for_contibuting_to_git_repos.git -b develop --single-branch
```
#### 2. For a new task or feature, create a new branch

> syntax: git checkout -b [mytask_myname]
e.g. 
```sh
$ git checkout -b adding_new_carousel_sanjeev
```
- Note that using `-b` with `checkout` creates a new branch and switches to it, while simply using `checkout` switches to a branch if it exists

#### 3. After task is done/ feature is created, and you are ready to commit, commit your branch

> syntax: git add [file] or use git add . for commiting all changes to all files

```sh
$ git add .

$ git commit -m "add info about changes here"

$ git push -u origin mytask_myname

# note that mytask_myname is the name of the new branch you are working in
```
#### 4. Switch to _develop_ branch and pull latest changes for it

```sh
$ git checkout develop

$ git pull origin develop
```

Now you are even with the develop branch (if you weren't already)
Note: Do this **only** after you have commited your existing changes, if any

#### 5. For a new task or feature, repeat steps 2-4

