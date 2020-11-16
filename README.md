# git-practices
Git basic workflow

![Git practices](https://github.com/dianavile/git-practices/blob/main/Git-Github.JPG)

## Essential Commands

- ```git init```
- init — Create an empty GIT repository in your development directory
- 1) Go to directory
- 2) git init

- ```git status```
- status — Show the current state of the repository including un-added and un-committed files

- ```git add .```
- add — Add a file to the repository staging area
- 1) Create a file, e.g. file.txt
- 2) git add file.txt
- 3) Add all new or changed files to the repository staging area (the period means all)

```git commit –m “Initial commit”```
- commit — Commit all changes to the repository for first time (-m means message)

- ```git commit```
- Commit all changes to the repository for later activities
git commit –m “Description of changes being made to project”

```git branch test```
- branch — Create a new branch of the project
- Choose a name for the new branch (original branch is master), e.g. test

- ```git branch```
-  List all branches (* appears next to current branch)

- ```git checkout```
- checkout — Switch branches and check-out all files (e.g. to test branch)

```git checkout –b test```
- Create a new branch and check-out files in one command

- ```git merge```
```git checkout master```
```git merge test```
- merge — Merge two branches together (go to the destination branch first, e.g. master)

```git branch test –d```
- (delete) — Delete a branch that you no longer need (e.g. after a merge)

- ```git log```
- log — View commit history (including long commit ID numbers)

- ```git revert```
- revert — Revert all files back to a previous commit point
- git revert <long commit ID from the log command>
  
```rm -cache```
- Removes cache from a specific file so that it can be added to the .gitignore

## Code-boilerplates
- [HTML5 boilerplate](https://github.com/h5bp/html5-boilerplate/blob/v4.3.0/doc/TOC.md)
- [JS Stack from Scratch](https://github.com/verekia/js-stack-from-scratch)
- [Bootstrap4](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
- [Responsive Design](https://github.com/verekia/initializr-template)

