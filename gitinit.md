[<<< Previous](gitconfig.md) | [Next >>>](github.md)

# Initialize a Repository

Using `cd`, navigate to the `git` folder inside `projects`. From your home direcotry, type:

	cd Desktop/projects/git

Now we're going to initialize our repository, which means telling Git to pay attention to it:

	git init

You should see output like this:

	Initialized empty Git repository in /home/patrick/projects/lalala/.git/

### Creating a Syllabus in Markdown

We are going to make our own syllabus as a plain text markdown file.

Let's use our text editor, nano, to create and edit a syllabus file in the folder. Type:

	nano syllabus.md

The `.md` extension means "markdown." XXX<symty edit> XXX

 ### Start your file.

Open your mysyllabus.md in your text editor. We have been using Sublime.

Give your document a title, insert your name and today's date. 

![alt text][syllabus start]

[syllabus start]: https://github.com/pswee001/Git_DRI_Jan_2018/blob/master/Screen%20Shot%202018-01-16%20at%202.01.04%20PM.png "How the start of your syllabus might look in sublime"

You'll notice that I added a # before my title, and two asterisks around my name. This is because I am using **markdown** to cue a heading, and to bold text. Try using markdown yourself to format your text! To make something show up on the next line, add two spaces at the end of each line. To make something appear as a new paragraph, leave an empty line in between. For reference, here is the [GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

CTRL + S saves the file, SHIFT + CTRL + W closes the Sublime window.

[<<< Previous](gitconfig.md) | [Next >>>](github.md)

[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
