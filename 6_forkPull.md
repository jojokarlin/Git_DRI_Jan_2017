#Fun with Forking

You **fork** a user's repository on **Github** in order to create a copy. Forking gives you the freedom to experiment without worry of compromising the source document.

![Evan's image of fork] (https://github.com/mckinniburgh/githubTutorial/blob/master/images/fork.png)

A **clone** is a local copy of a repository. We might think of **forking** as a way of cloning on Github, and **cloning** as a way of copying in git. Some users like to clone their repo after they've forked it; this means they can edit their local copy without having to be online, and then push changes once they're online again.

## Forking Practice

Partner up, and fork a file from your friend's repo on GitHub. Make a clone, and see if you can use the command line to open a file in the repo, make an edit, and send it back. 

Also, see if you can use the GUI on GitHub (just the buttons on the web page) to do the same thing. There should be a little edit button near the top of each repo.

Remember, what you don't know can be Googled or looked up on Stack Overflow!

### Commands to help

`git clone [URL of your GitHub repo]`

This clones a remote repo to your local Git so you can begin to edit. Many folks do this after forking the repo in GitHub's GUI (graphical user interface).

`git pull [URL of your GitHub repo]` 

If you receive an error notification that you are unable to push changes to your GitHub repo from your local repo, it often means that changes have been made to your GitHub repo that have not yet been logged locally. You'll have to pull the repo, then merge the changes by using `git commit -u origin master` (or whatever branch in which you're working) in order to return to smooth sailing with your `git push` commands. 