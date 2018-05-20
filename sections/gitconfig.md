[<<< Previous](commandline.md) | [Next >>>](markdown.md)

# Configure Git

Our first step in working with Git is configuring it with your own name and information.

## Check Your Install

Let's make sure Git has been successfully installed. In your terminal, type

	git --version

If you see a version number, you're all set. If not, click [here](http://git-scm.com/downloads) and install as you would any other software on your system.

## Configuring Git on Your Computer

Type the following into your command line, filling in the sections—below labelled "John Doe"—for your name and email. This does not necessarily need to be the name and email you used to sign up for GitHub.

	git config --global user.name "John Doe"
	git config --global user.email johndoe@example.com

To check your set-up, use:

	git config --list

You'll get something that looks like this:

	user.name=Superstar Git User
	user.email=gitsuperstar@gmail.com

[<<< Previous](commandline.md) | [Next >>>](markdown.md)
