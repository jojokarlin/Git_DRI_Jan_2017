[<<< Previous](github.md) | [Next >>>](gitrefresh.md)

# Add, Commit, and Push

You can use Git to track the different versions of a file by first _adding_ it so that Git is aware of the file you are interested in, second _committing_ the changes you made. This all happens on your **local computer**. When you want these changes to be visible on the remote repo you are connected to, you then _push_ it from the local to the remote.

## Making changes

Return to the mysyllabus.md you've made and add some readings or assignments.

Remember to save it!

## Git Add

In your working directory (GitPractice) in the command line, type:  
`git add mysyllabus.md`

This stages the file to be tracked, and prepares it to be committed.  

If you have been working on multiple files, `git add --all` adds all files if you have many to be tracked.

## Git Commit
Type: `git commit -m "[add a message here about the commits you're making]"`

Be brief but descriptive about changes in this version so that both you and your collaborators know the differences between your versions. 

##### Congrats! You've committed your first changes to your _local_ Git repo! 

It is good practice to check your status (make sure you're in the working directory) using:

`git status`

Git will tell you if changes have been made but not "staged" (i.e. not added) or committed. 

##### You can practice adding and committing by inserting these into your gitcheat.md file:

 - git status
 - git add
 - git commit -m "[message]"
 
Now, how do you get these changes onto GitHub so that others can see your good work?

## Git Push

Because our local and remote repos are connected, we can `push` our local repo to its remote directory. 

In the command line, type:

`git push origin master`

You'll then be prompted to enter your GitHub username and password.

Refresh GitHub in the browser to see your changes. 

---

[<<< Previous](github.md) | [Next >>>](gitrefresh.md)

[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
