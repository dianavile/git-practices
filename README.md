# git-practices
![Gitflow](https://github.com/dianavile/git-practices/blob/main/gitflow.JPG)

![Git practices](https://github.com/dianavile/git-practices/blob/main/Git-Github.JPG)

## Essential Commands

```git init``` — Create an empty GIT repository in your development directory
-  (Go to directory, git init)

```git status```— Show the current state of the repository including un-added and un-committed files

```git add .```— Add a file to the repository staging area
-  (Create a file, e.g. file.txt, git add file.txt, add all new or changed files to the repository staging area (the period means all))

```git commit –m “Initial commit”``` — Commit all changes to the repository for first time (-m means message)

 ```git commit```- Commit all changes to the repository for later activities
-  (git commit –m “Description of changes being made to project”)

```git branch```— Create a new branch of the project
```git branch test``` - Choose a name for the new branch (original branch is master), e.g. test

```git checkout``` — Switch branches and check-out all files (e.g. to test branch)
```git checkout –b test```- Create a new branch and check-out files in one command

```git merge``` — Merge two branches together (go to the destination branch first, e.g. master)
```git checkout master```
```git merge test```

```git branch test –d```— Delete a branch that you no longer need (e.g. after a merge)

```git log``` — View commit history (including long commit ID numbers)

```git revert``` — Revert all files back to a previous commit point-  git revert <long commit ID from the log command>
  
```rm -cache```- Removes cache from a specific file so that it can be added to the .gitignore

## Git - recourses 
- [Git basic workflow](https://cleventy.com/que-es-git-flow-y-como-funciona/#:~:text=Es%20ah%C3%AD%20donde%20entra%20en,a%20los%20lanzamientos%20del%20proyecto.)
- [Git guide](https://rogerdudler.github.io/git-guide/index.es.html)
- [Think lika a Git](http://think-like-a-git.net/)

## Code-boilerplates
- [HTML5 boilerplate](https://github.com/h5bp/html5-boilerplate/blob/v4.3.0/doc/TOC.md)
- [JS Stack from Scratch](https://github.com/verekia/js-stack-from-scratch)
- [Bootstrap4](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
- [Responsive Design](https://github.com/verekia/initializr-template)

