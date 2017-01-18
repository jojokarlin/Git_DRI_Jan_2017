# Git Day 2

##Welcome back!

First let's review. 

# Add, Commit, and Push
---
You can use Git to track the different versions of a file by first _adding_ it so that Git is aware of the file you are interested in, second _committing_ the changes you made. This all happens on your **local computer**. When you want these changes to be visible on the remote repo you are connected to, you then _push_ it from the local to the remote.

## Make changes to your 'cheat sheet'

Return to the gitcheat.md you've made and add some notes about the commands we have learned so far to it.

Add the commands we covered in yesterday's session:

- `git config --global user.name "[name]`
- `git config --global user.email "[email address]`
- `git config --list`
- `git init`
- `git remote add origin [URL of your remote repo]`
- `git remote -v`
- `git status`
- `git log`
- `git add .`
- `git commit -m "[clear message describing the changes you made]"`
- `git push origin master`

Remember to save it! 


## Challenge:

Navigate from your home directory into the folder we created yesterday.
From there check the status of your files.

---

## Git Add

Once you get into the working directory (e.g. GitPractice) in the command line, you can add any files you have modified.

`git add [filename]` stages a file to be tracked, and prepares it to be committed.  

If you have been working on multiple files, `git add --all` or `git add .` adds all files if you have many to be tracked.

Remember `git status` will show you what files have been staged.

## Git Commit
Type: `git commit -m "[add a message here about the commits you're making]"`

Be brief but descriptive about changes in this version so that both you and your collaborators know the differences between your versions. A common way of thinking about the description is "how would future me want find this version?" Be nice to future you -- don't overcomplicate it or overthink it.

#####How did you do? 
Put up a **red** or **yellow** sticky note. If you are yellow and your neighbor is red, see if you can help explain it. Teaching what you did may help you understand it better.

## Git Push

Because our local and remote repos are connected, we can `push` our local repo to its remote directory. 

In the command line, type:

`git push origin master`


Refresh GitHub in the browser to see your changes. 

###

## Challenge

- Create a README.md file in your GitPractice directory

- Save, stage, commit, and push your new file to your remote repo.

**hint** use a combination of command line and git commands.



## EXTRA Challenge
### Not for the faint of heart

- Initialize `git init` a *new* repository by navigating to your own project folder. 
- choose a directory you wish to track (it can be the cheatsheet directory or databases directory you made in the command line workshop)
- connect your local directory to your GitHub account
- put up your sticky note when you have made an initial commit to your GitHub 



[<<< Add push pull](gitaction.md) - [Challenge yourself >>>](gitchallenge.md)  
[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)