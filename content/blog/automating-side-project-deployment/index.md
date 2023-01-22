---
title: "[WIP] Automating the Building and Deployment of Full-Stack Side Projects for Dummies"
date: "2023-01-21T00:00:00"
description: "I'll attempt to figure out an easy way to automate building and deploying frontend and backend artifacts for my side projects without. I'll try to avoid making too many assumptions about knowledge of various different technical aspects to hopefully make this guide useful for those new to full-stack software development.  Maybe solving this personal pain point of mine and creating a cloneable template I can use to kickstart new projects will motivate me to push more frequently."
---

## Picking and sticking to a Git workflow strategy

Git workflow strategies are processes and practices that a team uses to manage their Git versioned codebase. These strategies can include everything from how code is written and reviewed, to how it is tested and deployed. I'll note common strategies below as well as the strategy I'll try to adhere to for my full-stack side projects.

I referenced Gitlab's ['What is a Git workflow'](https://about.gitlab.com/topics/version-control/what-is-git-workflow/#:~:text=A%20centralized%20Git%20workflow%20enables,without%20using%20any%20other%20branch.) article when putting the below summaries together. Review Gitlab's article for a more detailed write-up.

### Common Git workflow strategies

#### Centralized Workflow

All commits are made to the main branch of a repository. Not ideal when multiple developers are working on the codebase. Usually utilized by small teams, people new to using Git, or codebases that are updated infrequently.

#### Feature Branch Workflow

Whenever developing a new feature or bug-fix, create a branch, make changes, submit a merge request (or pull request), and then merge it into main. The main branch remains clean and stable, meaning it should always build and run without issues. Ideal for codebases where multiple developers are working simulataneously.

#### Gitflow Workflow

This is a more robust version of the Feature Branch Workflow. The main branch should always be releasable to production. When using this Git workflow, no one commits to the main branch but rather uses a develop branch with feature branches. When the develop branch is ready to go to production, a contributor creates a release branch where testing and bug fixing occur before being merged back to the develop branch. It also includes release branches and hotfix branches for emergency bug fixes.

#### Forking Workflow

This workflow uses forks of the main repository, which creates a local copy of a Git repository. This allows developers to work on their own copy of the repository and submit a merge request (or pull request). Popular for open source projects with many developers.

TODO:

## My Git workflow strategy of choice

## Gitlab Workflows to automate artifact building

## Gitlab Workflows to deploy containers
