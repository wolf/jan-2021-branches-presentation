# Using Branches in Git

(Separation of concerns: good in your code, good in your coding.)


## Why am I talking about branches?

* Because they can help you get your work done faster and more easily.
* Because they can help you collaborate with others.


## What do I want you to come away with?

* The desire to use branches, and enough knowledge to benefit from them.


## What are the most important things I can teach you?

* Branching is quick and easy.
* Branches let you handle multiple problems at once.  Your work on each problem is totally independent.
* Commit often.  Commit before switching (unless you are explicitly trying to take your changes with you to the new branch).
* Merge puts your commits onto the target branch.
* Rebase moves your branch from one place to another but it's still just a branch; you need to merge to get your commits onto the target branch.


## What are the key benefits that could really make you happy?

* Scenarios you are in today where branches could have helped.
    * You have commits you want to push, and others that are not ready.  People come to me often with this.
    * You had to stash all your changes so you could work on an emergency bug fix.
    * You have a bunch of local changes that you want to save, maybe for a long time.
    * You're making lots of small commits, but you just want one big fat commit to land on main.


## What are the major pitfalls that could really screw you up?

* Merge conflicts
* Your loose changes try to come with you when you switch branches.  Commits stay on the branch on which they were made.
* Rebasing commits upon which other people have based their work


## Branching

## Merging

## Rebasing

## Merge Requests on GitLab


## Points to Cover

* Visualizing branches
    * IntelliJ
    * Gitk
* What is a branch?
    * We already use branches: main, and the release branch
    * What a branch is physically
    * What a branch is with respect to your actual work
* Branch basics
    * How to make a new branch
    * How to switch between branches
    * How to push a branch for the first time
    * How to delete a branch on the server
    * How to delete a branch locally
    * How to merge a feature branch into main
    * Working on a long-term branch
        * How to keep up with main
        * Working on someone else's branch
        * Force-pushing rebased branches
    * Quick little branches

    * Terminology
        * HEAD is where you're at right now
        * 'the tip' of the branch, and the branch name itself both refer to the newest commit on the branch
        * Usually `HEAD` and the tip of the branch refer to the same commit
        * Fast-forward
        * Merge "bubble"
    * The difference between a branch and a tag
* Why use branches?
* What are the pros and cons?
* When not to use a branch
* Local-only branches
* Branches you push up to the server
    * Why would you push a branch up to the server?
    * What is a remote tracking branch?
* Long-term shared branches
* Pulling and pushing branches other than main

* Merge "bubbles" and straight lines
    * The impact of working on a large team

* All about Merge Requests
    * What are they good for?

* Things IntelliJ does for you
    * you can just start typing in the branch menu (any branch menu)
        * and you can start typing into the menu that pops up _out_ of a branch, too
    * Saves and restores your workspace when you switch branches
    * Ways to tell you what you're in the middle of (and the power to abort it)
    * Multiple log tabs in the Git panel (you should always have one set to show everything)
* Things GitLab does for you

* Do I want to talk about detached heads?

## Resources

* [Learn Git Branching](https://learngitbranching.js.org/)
* Pro Git: [Git Branching](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)
* Pro Git: [Git Tools - Advanced Merging](https://git-scm.com/book/en/v2/Git-Tools-Advanced-Merging)


## Things Specifically _Not_ to Cover

* Interactive rebase

狼









<!-- vim: set ts=4 sw=4 tw=0 et ai :-->
