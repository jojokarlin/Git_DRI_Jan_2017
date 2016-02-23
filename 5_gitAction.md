### Steps for committing changes

# Add, Commit, and Push

Always check the status (make sure you're in the working directory):

`git status`

## Git Add

In your working directory in the command line, type:

`git add [name].md`

This stages the file to be tracked, and prepares it to be committed. 

## Git Commit

Use the command:

`git commit -a`

`-a` commits all files that have been added. A text editor will then open up and prompt you to enter a description of changes. Be concise! For Nano, press `^O` to save, hit `enter`, and then `^x` to exit. 

You can also type:

`git commit -m "(add a message here about the commits you're making)"`

This will let you type your message right into the command line. 

Remember, being brief but descriptive about changes will let both you and your collaborators know the differences between your versions. 

Congrats! You've committed your first changes to your Git repo. 

## Setting up Your Remote Repo

Now, let's add this directory to GitHub so we can share it with others and start collaborating.

- Go to **GitHub** in your browser and click the plus sign in the upper right hand corner to create a new remote repo. 

- Give it the same name as your local repo. Skip the "add README.md" step, since you're importing an existing directory.

- Navigate to your new remote repo in the browser, and copy its HTTPS: URL. 

In the **command line**, check your git status

`git status`

and make sure all your commits are up to date. When they are, type

`git remote add origin [URL of your remote repo]` 

This will link the local and remote repo. To confirm, type:

`git remote -v`

If you're getting stuck, setting up a [remote repo in GitHub](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) is a good resource.

## Git Push

Now that our local and remote repos are connected, let's `push` our local repo to its remote directory. 

In the command line, type:

`git push -u origin master` (this pushes to the master branch)

You'll then be prompted to enter your GitHub username and password. Complete this step, then refresh GitHub in the browser to see your changes. 

Cheer wildly!