# Improvements

## Topics
* Vim pop up screen
* Creating/Deleting folders
* Rebase vs. Merge

## Script
1. A real project
    - .gitignore
    - React frontend
    - Widgets
2. Topics this will hit:
    - Checking out a feature branch
    - Show a merge and a rebase
    - Show resolving a merge conflict (how to handle VIM)
    - Reviewing a PR: both rejecting and approving
    - renaming a folder
3. What we're actually doing:
    - Josh checks out a feature branch `update-board`. Make slight changes, and push it up and make a PR.
    - Andrew reviews the PR, requests changes.
    - Josh fixes, resubmits it.
    - Andrew approves. Josh (and Andrew) needs to remember to update his local master branch. Delete old
    local feature branch. Start a new one to work on the next feature.
    - Andrew checks out feature branch `more-board`. Makes changes, pushes it up and makes a PR.
    - Josh checks out different feature branch `most-board`, makes changes, pushes it up and makes a PR.
    Josh approves Andrew's PR before Andrew approves Josh's, causing Josh's PR now to have merge conflicts.
    - Josh demos how to resolve merge conflicts, BEFORE submitting the pull request.
      - Pulling down master into the feature branch, and locally resolving before create the pull request.
      - Puts the head flags in your code
      - Also can see conflicts with git status
      
    - All the while, the actual branching is being displayed on the board.

## Vim Cheat Sheet
https://www.fprintf.net/vimCheatSheet.html