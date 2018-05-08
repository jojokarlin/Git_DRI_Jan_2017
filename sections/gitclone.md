[<<< Previous](gitchallenge.md) | [Next >>>](gitpullreq.md)

# Making a copy of a GitHub repo to work on locally

## Cloning

A **clone** is a local copy of a repository.  

(A **fork** is a copy of a repository, on GitHub.) 

![alt text][git-clone]

[git-clone]: https://github.com/jojokarlin/Git_DRI_Jan_2017/blob/master/images/git-clone.png "git-clone image from http://www.jonathanpberger.com/" 

`git clone [URL of your GitHub repo]`

This clones a remote repo to your computer so you can customize it to your taste. 

**First, make sure you are out of GitPractice before you clone.** Let's navigate to the Desktop. 

Clone the [repo for my hypothetical course syllabus](https://github.com/pswee001/Syllabus) so we can see what cloning a repository is like!

`git clone https://github.com/pswee001/Syllabus`

Also, you can use the GUI (graphical user interface) on GitHub (buttons on the web page) to do the same thing. There should be a little "clone or download" button near the top right of each repo. 

You can find many of the workshops from this week linked in the Digital Fellows' [curriculum page](https://gcdigitalfellows.github.io/january_2018_curriculum.html). You can `clone` individual repositories of those workshops you might wish to revisit or that you might wish to copy to teach yourself.

[dolly]: https://github.com/jojokarlin/Git_DRI_Jan_2017/blob/master/images/dolly.htm "Dolly the Sheep by Gary Henderson Attribution	Noncommercial	 Share Alike " 

## Challenge 

- `git push` your updates to the syllabus so they show up on your Github.com account:

- Create a new repository at github.com. (this is your repository)

- Give it the same name as as the repository you cloned.
*Don't initialize it with a README, .gitignore, or license.*

- `git remote set-url origin https://github.com/your-account/your-repository.git` Push the local repository to your repository on github.

**don't forget! you must *add,* *commit,* before *push*ing!**

- `git push origin master`


___

[<<< Previous](gitchallenge.md) | [Next >>>](gitpullreq.md)

[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
