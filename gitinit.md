[<<< Previous](gitconfig.md) | [Next >>>](github.md)

# Initialize Git

Using `cd`, navigate inside the folder 'GitPractice.' 

Type `git init` and hit enter.

This initializes the Git repository so it knows to pay attention to this folder. 

You should see something like `Initialized empty Git repository in /Users/gcdri/Desktop/GitPractice/.git/`

### Create a file in your folder.  

We are going to make our own cheatsheet as a plain text markdown file.

Make sure you've navigated inside your GitPractice folder. Use `cd` or `cd ..` as needed.

Type `touch MySyllabus.md` The '.md' extension means "markdown." You can use `touch` to create other types of files too: `touch [name].[extension]`.

### Start your file.

Open your MySyllabus.md in your text editor. We have been using Sublime.

Give your document a title, insert your name and today's date. 

![alt text][syllabus start]

[syllabus start]: https://github.com/pswee001/Git_DRI_Jan_2018/blob/master/Screen%20Shot%202018-01-16%20at%202.01.04%20PM.png "How the start of your syllabus might look in sublime"

You'll notice that I added a # before my title, and two asterisks around my name. This is because I am using **markdown** to cue a heading, and to bold text. Try using markdown yourself to format your text! To make something show up on the next line, add two spaces at the end of each line. To make something appear as a new paragraph, leave an empty line in between. For reference, here is the [GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

CTRL + S saves the file, SHIFT + CTRL + W closes the Sublime window.

[<<< Previous](gitconfig.md) | [Next >>>](github.md)

[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
