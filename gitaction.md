# Add, Commit, and Push

You can use Git to track the different versions of a file by first _adding_ it so that Git is aware of the file you are interested in, second _commiting_ the changes you made. This all happens on your local computer. When you want these changes to be visible on the remote repo you are connected to, you then _push_ it from the local to the remote.

Always check the status (make sure you're in the working directory):

`git status`

## Making changes

If you closed it, let's open up the cheatsheet we just made.  
`open gitcheat.md`

Or, if it's already open, add the things we have learened so far to it.

Let's start with these:

- git config -- global user.name "[name]
- git config --global user.email "[email address]
- git config --global core.editor "subl -n -w"
- git config --list

Remember to save it!

## Git Add

In your working directory in the command line, type:

`git add gitcheat.md`

This stages the file to be tracked, and prepares it to be committed.  

If you have been working on multiple files, `git add --all` adds all files if you have many to be tracked.

## Git Commit
Type: `git commit -m "[add a message here about the commits you're making]"`

Be brief but descriptive about changes in this version so that both you and your collaborators know the differences between your versions. 

Congrats! You've committed your first changes to your _local_ Git repo.

To commit and add at the same time, use the command:  
 `git commit -a`  
 `git commit -am "[message about the commits]"` 

####You can practice by inserting these to your gitcheat.md file:
 - git status
 - git add
 - git commit -m "[message]"

and even this command we will be explaining below  
 - git push -u origin master
 
Now, how do you get these changes onto a shared GitHub so that others can see your good work?

## Git Push

Because our local and remote repos are connected, we can `push` our local repo to its remote directory. 

In the command line, type:

`git push -u origin master` (this pushes to the master branch)

You'll then be prompted to enter your GitHub username and password.  
Refresh GitHub in the browser to see your changes. 

####Cheer wildly!

Subsequently, you can just use `git push`
___
[<<< Connect GitHub](github.md) - [Making a copy from GitHub >>>](gitpull.md)  
[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
