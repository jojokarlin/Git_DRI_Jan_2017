[<<< Previous](commandline.md) | [Next >>>](markdown.md)

# Configure Git

First, we're going to configure Git using the command line.  

#### Open your terminal

Mac: press the space bar and the command key at the same time and type in "terminal."

Windows: launch the command prompt from the run window. 

#### Check your install

Type `git` at the `$` prompt.

If you get a nice list of commands, you're good to go. If not, click here [here](http://git-scm.com/downloads) and install as per the directions.

## Configuring Git on your computer

Type the following into your command line, filling in the sections for your username and email. These must correspond to the name and email you used to sign up for GitHub.

`git config --global user.name "John Doe"`

`git config --global user.email johndoe@example.com`

To check your set-up, use:

`git config --list`

You'll get something that looks like this:

`user.name=Superstar Git User`  
`user.email=gitsuperstar@gmail.com.`  

[<<< Previous](commandline.md) | [Next >>>](markdown.md)
