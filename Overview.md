# Overview of the Git Kata Exercises

## Setup

1. [configure-git](configure-git/README.md) - If git is not configured, some basic configuration steps

## Basic Git Katas in Suggested Order

1. [basic-commits](b01-basic-commits/README.md) - Very basic creation of commits.
2. [basic-staging](b02-basic-staging/README.md) - Interacting with the stage (index).
3. [basic-branching](b03-basic-branching/README.md) - The first stride into branching.
4. [ff-merge](b04-ff-merge/README.md) - A tour around the most trivial of merges.
5. [3-way-merge](b05-3-way-merge/README.md) - A basic merge, involving multiple diverged branches.
6. [merge-conflict](b06-merge-conflict/README.md) - A basic merge between diverging branches with incompatible (but simple) changesets.
7. [merge-mergesort](b07-merge-mergesort/README.md) - A merge conflict with actual code.
8. [rebase-branch](b08-rebase-branch/README.md) - Using rebase as an alternative to merging.
9. [basic-revert](b09-basic-revert/README.md) - Use revert to revert a change
10. [reset](b10-reset/README.md) - Reset is a powerful and slightly dangerous command if you do not know what you are doing. Go through the three modes of resetting here.
11. [basic-cleaning](b11-basic-cleaning/README.md) - Cleaning the workspace.
12. [amend](b12-amend/README.md) - Amending previous commits.
13. [reorder-the-history](b13-reorder-the-history/README.md) - We might have created our commits in a suboptimal order, practice to fix that scenario here.
14. [squashing](b14-squashing/README.md) - A lot of small commits is good when you are working locally, but for sharing your code, it might be more beneficial to deliver your code changes in large sets. Go here to experiment with that. Write a good commit
15. [advanced-rebase-interactive](b15-advanced-rebase-interactive/README.md) - Practice using the interactive rebase commands.
16. [basic-stashing](b16-basic-stashing/README.md) - The first stride into stashing.
17. [ignore](b17-ignore/README.md) - The basics of using the `.gitignore` file. And using `git rm`.
18. [submodules](b18-submodules/README.md) - Submodules are loathed by many. Run through this exercise to see what the ruckus is all about.
19. [git-tag](b19-git-tag//README.md) - Tags are convenient for keeping track of commits that bump a version number. In this exercise, you will list, add and delete tags.

## Katas that solve standard problems

1. [commit-on-wrong-branch](p01-commit-on-wrong-branch/README.md) - If we accidentally put unpushed commits on the wrong branch, how do we effectively _move_ them to another branch before our work on that branch.
2. [commit-on-wrong-branch-2](p02-commit-on-wrong-branch-2/README.md) - Another exercise on what to do if you have accidentally committed on the wrong branch.
3. [reverted-merge](p03-reverted-merge/README.md) - We revert a merge, but, after fixes are added to the merged branch, we want the changes from merge and the new fixes.
4. [save-my-commit](p04-save-my-commit/README.md) - Should you accidentally or on purpose delete a commit, go here to try and save it. You will use the reflog.
5. [detached-head](p05-detached-head/README.md) - git complains that you are in a "You are in 'detached HEAD' state". What do you do?

## Katas On Advanced features

1. [git-attributes](a01-git-attributes/README.md) - .gitattributes file allows you to specify how git handles files, such as line endings in text files or how to diff a binary file.
2. [Bad-commit](a02-bad-commit/README.md) - Using `git bisect` to find a bad commit.
3. [bisect](a03-bisect/README.md) - Another kata using `git bisect`.
4. [pre-push](a04-pre-push/README.md) - A quick exercise in using Git hooks.
5. [Investigation](a05-investigation/README.md) - Discover what is going on in a Git repo, figure out what it looks like under the hood.
6. [Objects](a06-objects/README.md) - A small exercise into Git internals.
7. [merge-driver](a07-merge-driver/README.md) - Defining a custom merge driver.
8. [rebase-exec](a08-rebase-exec/README.md) - Run tests on every commit using `git rebase --exec`
