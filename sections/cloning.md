[<<< Previous](gitaction.md) | [Next >>>](challenge.md)

# Cloning

**Cloning** a repository means making a copy to work on locally. When you clone a repository from GitHub, information about where it was cloned from will automatically be added to your local version. This means that commands like `git push` will work without adding additional information.

	git clone <repository-url>

For practice, let's clone the repository for this session about Git and GitHub.

First, let's navigate back to your Desktop folder.

	cd ~/Desktop
	
Remember that the ~ refers to your home directory. Now let's find the URL we need to clone the lesson.

First, follow [this link to the main page of this lesson on Git and GitHub](https://github.com/DHRI-Curriculum/git).

On the main page, there should be a green `Clone or download` button on the right side:

![Image pointing out where the clone or download button is on GitHub](clone.png)

Click the green button and you will see a box with highlighted text under a heading that says `Clone with HTTPS`. If you instead see `Cloning with SSH`, click the small link that says `Use HTTPS`.

Now copy out the text in the box:

![Image showing where the text you need to copy is located](copy-clone-text.png)

Now that you have the text copied, go back to your terminal. Remember, you should be on the desktop.

Type

	git clone <copied-url>
	
If the command is successful, the full Git lesson will be replicated on your local machine. You can type

	cd git
	
to enter the lesson folder, since the lesson repository is simply called `git`. Use the `ls` command to take a look at the various files in the lesson folder.

[<<< Previous](gitaction.md) | [Next >>>](challenge.md)
