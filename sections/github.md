
[<<< Previous](markdown.md) | [Next >>>](gitaction.md)

# Connecting to GitHub

Now, let's connect the directory you made to GitHub. GitHub is a service that allows us to host files, collaborate, and find the work of others. Once our syllabus is on GitHub, it will be publicly visible.

Go to GitHub in your browser and click the plus sign in the upper right hand corner to create a new remote repo. 

![You can find the plus sign button to add a repo on the top right of github](images/addrepo.png)

- Give it the same name as your local repo. 
- Select Public 
- *Do not* select "Initialize this repository with a README" since you will be importing an existing directory.
- Click Create repository

[createrepo]: https://github.com/jojokarlin/Git_DRI_Jan_2017/blob/master/images/createrepo.png "select 'new repository' from your dropdown menu"
[createrepo2]: https://github.com/jojokarlin/Git_DRI_Jan_2017/blob/master/images/createrepo2.png "what it should look like when you are creating your repo"

- You should end up inside your newly created GitPractice repo. If not, navigate to your new remote repo in the browser, and copy its HTTPS: URL (highlighted in light blue).

![alt text][github URL]

[github URL]: https://github.com/jojokarlin/Git_DRI_Jan_2017/blob/master/images/github%20URL.png "copy the URL from your browser"

On your command line, type `git remote add origin [URL of your remote repo]`  
This will link the local and remote repo.  

To confirm, type `git remote -v` and hit enter.

You should see something like  
`Origin https://github.com/jojokarlin/Git_DRI_Jan_2017 (fetch)`  
`Origin https://github.com/jojokarlin/Git_DRI_Jan_2017 (push)`

If you're getting stuck, setting up a [remote repo in GitHub](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) is a good resource.

---


[<<< Previous](markdown.md) | [Next >>>](gitaction.md)
