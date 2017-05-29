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
    - Josh checks out a feature branch `update-weather`. Make slight changes, and push it up and make a PR.
    - Andrew reviews the PR, requests changes.
    - Josh fixes, resubmits it.
    - Andrew approves. Josh needs to remember to update his local master branch. Delete old 
    local feature branch. Start a new one to work on the next feature. 
    - Andrew checks out feature branch `more-weather`. Makes changes, pushes it up and makes a PR.
    - Josh checks out different feature branch `most-weather`, makes changes, pushes it up and makes a PR. 
    Andrew approves Josh's PR before Josh approves Andrew's, causing Andrew's PR now to have merge conflicts.
    - Andrew demos how to resolve merge conflicts. 
    - All the while, the actual branching is being displayed on the board.
