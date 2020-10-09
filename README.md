# WhatIsThis_Backend

## Version Control
For the course of this project, the branching strategy will involve using [git flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).

This means we will use a master branch for releases and a develop branch to work off of for integrating features. See link above for a more detailed explanation. Whenever a new feature is to be implemented, a feature branch will be created. It's highly recommended that you check out the link above as it will give you a better understanding of what this branching strategy is. This will align with our Rally tickets. The format for creating a new branch is as follows:

*TicketNumber*/*type*-*name*

See an example below

If the rally ticket number is TA111 and it's title is "Implement login feature" it is a feature, then the branch will be named as follows
    TA111/feature-implement-login-feature

If the rally ticket is TA111 "Fix login bug" for a bug fix it will look like 
    TA111/bug-fix-login-bug

Remember, everytime you wish to create a new feature, branch off of develop. This will help to avoid merge conflicts, make it easier to code review changes, amongst many other benefits.

If there is any confusion, see the link above, or talk to the team leader.

If you need a refresher on git, there is a good cheatsheet [here](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet).