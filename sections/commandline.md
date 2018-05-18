[<<< Previous](examples.md) | [Next >>>](gitconfig.md)  
# Review of the Command Line

We'll be using the command line in this session, so let's review some command line basics first, including navigation. For more on the command line, review the [materials for the command line session](https://github.com/DHRI-Curriculum/command-line).

## Accessing the Terminal

### Mac OS

Press the space bar and the command key at the same time and type `terminal`. Press `Enter`.

### Windows

Press the Windows button on your keyboard. When the search menu pops up, type `git bash` and press `Enter`.

## Practice Navigating the Command Line

In this session, we will be making a syllabus and using Git to keep track of our revisions. Let's create a Git project folder

	cd <directory-name> 
	
will let you navigate inside a directory of your choosing.

Type 

	cd Desktop
	
and hit `Enter`. This will change your current working directory from `/Users/<your-name>` to `/Users/<your-name>/Desktop`.

To check your current directory, type

	pwd
	
Try this now to make sure you're in your Desktop directory.

Now, use 

	cd ..
	
to go up one directory. In this case, this will take you back to your home directory.

Practice going back and forth between your Desktop and your home directory.

When finished, go to your Desktop folder and check that you're there with `pwd`.

## Making a Git Project Folder

If you've worked through the command line session, you should see a `projects` folder on your desktop. Navigate into it with

	cd projects
	
If you don't have a projects folder on your desktop, create one with

	mkdir projects

From `Desktop`, navigate into your `projects` folder. Then create a `git` folder with the below command:

	mkdir git

Enter the new `git` folder with

	cd git

At this point, when you type `pwd`, Your folder structure should look like this:

	/home/<username>/Desktop/projects/git

[<<< Previous](examples.md) | [Next >>>](gitconfig.md)  
