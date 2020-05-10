---
layout: post
title: Git Cheatsheet
date: 2019-12-05
tags: cheatsheet
---

## Create or clone
`git init` - turns the current local directory into a repository

`git clone <URL>` - clone an existing repository


## Local changes
`git status` - see what changes were made in your working directory and what files are staged for commit

`git add <file>` - add a file to what will be committed; can use wildcard (\*) if want to add multiple files

`git commit -a`- commit all local changes in tracked files

`git commit -m [update message]` - commit with an update message


## Update and Publish

`git remote -v` - to see the current configured remote URLs

`git remote add <shortname> <URL>` - add a new remote repository 

`git remote set-url <shortname> <link>` - update the repository link (for example, when you want to switch from HTTPS to SSH)

`git push` - publish changes to remote

`git fetch <remote>` - download changes from <remote> but don't integrate into HEAD

`git pull <remote> <branch>` - download changes and directly merge/integrate into HEAD 




