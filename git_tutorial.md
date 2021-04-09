# Git Turtorial

## Git Introduction
This page is my best interprestation of how Git works and what cool things you can do to get a better udnerstanding of what git is all about.   

Creating a new remote Git repository.  
```
git remote add shortname url
```
 
EX: 
```$ git remote

origin

$ git remote add js https://github.com/janesmith/project1

$ git remote -v

origin https://github.com/johndoe/project1 (fetch)

origin https://github.com/johndoe/project1 (push)

js     https://github.com/janesmith/project1 (fetch)

js     https://github.com/janesmith/project1 (push)

Fetching 
```

- Fetching entails pulling data that is no present from a remote project. 

Formatting: git fetch [remote-name] 

## Cloned repositories 
- For cloned repositories, use command (git fetch origin)
- Pulls down any new changes that were pushed to the server since you cloned or last fetched from it. 

Pushing 

git push [remote-name][branch-name]

Example:
$ git push origin master
*This command pushes committed changes from your local “master” branch upstream to the “origin” server.
Note: You can only successfully push changes upstream if you have write access for the server from which you cloned, and if someone else has not pushed changes upstream that you haven’t pulled yet. If a collaborator pushed changes upstream after you had cloned, your push will not be successful. You will have to pull new changes and merge them with your branch before you can successfully push your changes upstream.