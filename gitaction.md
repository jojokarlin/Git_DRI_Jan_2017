# Add and Commit

Continuing the musical metaphor, _adding_ calls your file out of the dressing room.

Always check the status (make sure you're in the working directory):

`git status`

## Making changes

let's open up the cheatsheet we just made and add the things we have learened so far to it.

`subl cheatsheet.md`

Let's start with these:

- `git config -- global user.name "[name]`
- `git config --global user.email "[email address]`
- `git config --global core.editor "subl -n -w"`
- `git config --list`

Remember to save it!

## Git Add

In your working directory in the command line, type:

`git add [name].md`

This stages the file to be tracked, and prepares it to be committed.  
So let's stage the cheatsheet we added text to to be tracked.

`git add cheatsheet.md`

If you have been working on multiple files, `git add --all` adds all files if you have many to be tracked.

## Git Commit

To commit a file, type:

`git commit -m "(add a message here about the commits you're making)"`

Remember, being brief but descriptive about changes will let both you and your collaborators know the differences between your versions. 

Congrats! You've committed your first changes to your local Git repo. Now, how do you get these changes onto a shared GitHub so that others can see your good work? How do you get your files to get on the stage to dazzle the audience?

To combine the commit and add stage, use the command:

`git commit -a *`

`-a *` commits all files in the repo. `-a file` commits the file listed after `-a`.

---
[<<< Initialize Git](gitinit.md) - [Git push >>>](gitpush.md)  
[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
