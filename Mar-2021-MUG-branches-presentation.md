# Using Branches in Git

(Separation of concerns: good in your code, good in your coding.)


## Why am I talking about branches?

* Because they can help you get your work done faster and more easily.
* Because they can help you collaborate with others.


## What do I want you to come away with?

* The desire to use branches, and enough knowledge to benefit from them.


## What are the most important things I can teach you?

* Branching is useful quick and easy
* Branches let you handle multiple problems at once
* Commit often.  Commit before merging, rebasing, or switching (unless you are explicitly trying to take your changes with you to another branch)
* Merge puts your commits _onto_ the target branch
* Rebase moves your branch from one place to another but it's still just a branch, you need to merge to get your commits onto the target branch
* Branching, merging, and rebasing all work together


## What are the key benefits that could really make you happy?

* You have commits you want to push, and others that are not ready
* You had to stash all your changes so you could work on an emergency fix
* You have changes you can't put onto the main branch, but you want to save them ... maybe for a long time
* You're have lots of small commits (that's good!), but you just want one big fat commit to land on main
* You want to try an experiment
* You want to see if _your_ changes introduced the bug


## What are the major pitfalls that could really screw you up?

* Merge conflicts
* Your loose (uncommitted) changes try to come with you when you switch branches.  Sometimes this is a benefit.  Sometimes it's a hazard.
* Rebasing commits upon which other people have based their work


## Branching

* What is a branch?
* How do branches work inside Git?
* Git commands to deal with branches


## Merging


## Rebasing


## Workflows


## Resources

* For branching
    * [Learn Git Branching](https://learngitbranching.js.org/).  This website is *really* good (it's just too bad all the trees are drawn upside-down).  I _strongly_ recommend this website for everyone
    * Pro Git: [Git Branching](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)
    * Pro Git: [Git Tools - Advanced Merging](https://git-scm.com/book/en/v2/Git-Tools-Advanced-Merging)
* For Git in general
    * [tig](https://github.com/jonas/tig)
    * [fugitive](https://github.com/tpope/vim-fugitive) is _the_ most popular plugin of any kind for Vim.  It makes Git easy inside Vim.


## Points to Cover

* Everybody is moving to `main` over `master`
* Each branch gets its own reflog
* Visualizing branches
    * git log --graph
    * Gitk
    * other cross-platform tools?
* What is a branch?
    * We already use branches: main, and the release branch
    * What a branch is physically
    * What a branch is with respect to your actual work
* Branch basics
    * How to tell Git to name your primary branch `main` instead of `master`
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

* Do I want to talk about detached heads? Yes!

<!-- vim: set ts=4 sw=4 tw=0 et ai :-->
