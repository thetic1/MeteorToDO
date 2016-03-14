# DGM3780 Meteor #

# Build instructions #

# What you learned #
Meteor uses mongo collections. It also has a great built in way to manage users and user sessions. Which would actually be pretty handy on my project.

# What you found difficult #
Some of the error messages were not specific enough for me to tell where I had gone wrong in the tutorial.

# What are the advantages to branching in Git? #
It allows you to develop new features with affecting the master version. This is especially useful for experiments that you aren't sure you want on the master branch yet.

# Researh two types of git workflows, and describe their process. (Gitflow, Github Workflow, Forking Workflow, Centrlized Workflow. ETC.) #

Github Workflow: Branch->Commit->Pull->Discuss and review->Deploy
Gitflow Workflow: Central Repository, Two branches. Master Branch is official release. Develop branch is used to add features. Each feature has its own branch of the develop branch. 

Once develop has enough features you fork a branch and this becomes your release, a new release cycle begins. No new features except for bug fixes can be added.

once its ready to ship the release branch is tagged with a version number and merged into the master branch

# What are the advantages and disadvantages of each workflow. #
Github workflow makes it easy for anyone to make changes to your code and request the changes be merged back in. However with this method each developer must maintain their own forked repository and make sure its up to date with the central repository. There is also no guarentee your changes will be accepted into the central repository.

GitFlow make it possible for teams to polish the current release while others work on new features. It also creates recognizable development phases. However the multiple branches may become confusing and make the project history difficult to follow.