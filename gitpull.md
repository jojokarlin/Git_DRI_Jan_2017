#Making a copy of a GitHub repo to work on locally
## Cloning

A **clone** is a local copy of a repository.  

`git clone [URL of your GitHub repo]`

This clones a remote repo to your local Git so you can begin to edit it. 

####Option 1

Clone the [repo for this workshop](https://github.com/jentang/GitDRI) so you can have a copy for yourself!

`git clone https://github.com/jentang/GitDRI`

Also, see if you can use the GUI on GitHub (just the buttons on the web page) to do the same thing. There should be a little "clone or download" button near the top right of each repo. 

####Option 2

We will be using the [New York Public Library's database](https://github.com/GCDigitalFellows/nypl_data) for Ian's databases workshop tomorrow, so let's make a clone of it now.

`git clone https://github.com/GCDigitalFellows/nypl_data`

## Pulling

If you receive an error notification that you are unable to push changes to your GitHub repo from your local repo, it often means that changes have been made to your GitHub repo that have not yet been logged locally. You'll have to pull the repo, then merge the changes by using `git commit -u origin master` in order to return to smooth sailing with your `git push` commands. 

`git pull [URL of your GitHub repo]`

Remember, what you don't know can _always_ be Googled or looked up on Stack Overflow!  
___
[<<< Git add, commit, and push](gitaction.md) - [Return to repo](https://github.com/jentang/GitDRI)  
[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
