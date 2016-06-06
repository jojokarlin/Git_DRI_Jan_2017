## Command Line Basics

In contrast to a GUI, or graphical user interface, the command line lets us tell our computer exactly what we want it to do using successive lines of text. 

The commmand line is one of the primary ways of using Git on your computer. We're going to use this method practice what we learned yesterday, and help us grasp the concepts of Git (and feel like we have computational superpowers, making files appear out of thin air). To review...

### Open your Terminal. 

Mac: press the space bar and the command key at the same time and type in "terminal."

Windows: launch the command prompt from the run window. 

### Go to your Desktop.

`cd [name of directory or folder]` will let you navigate inside a directory of your choosing.

Type `cd Desktop` and hit enter.

Now, `cd ~` lets you go back a directory.

Practice going back and forth between your Desktop and your home directory. Experiment! The more you type the more natural the command line will feel. 

Got lost?

`pwd` or "print working directory" will tell you where you are if you get a little lost.

End on your Desktop. 

### Make a new folder on your Desktop.

`mkdir` makes a new directory.

Type `mkdir GitPractice` and hit enter. 

Click around to go check out your desktop and see your new folder. 

### Initialize Git. 

Using `cd`, navigate inside the folder 'GitPractice.' 

Type `git init` and hit enter.

This initializes the Git repository. It _sets the stage_ for the magic you want to create! Now, by using commands like `git add` and `git commit`, you can track changes to your documents. More on this soon...

### Create a file in your folder. 

Back in the command line, we're going to make a plain text markdown file.

Make sure you're navigated inside your GitPractice folder. Use `cd` or `cd ..` as needed.

Do you remember how to create a file?
 
Hint: type `touch [name].md` The '.md' extension means "markdown." You can use `touch` to create other types of files, too.

### Edit your file.

`open [name].[extension]` will let you get started.

Whatever text editor pops up should be the one that you set in your `git config`. We have configured it to use Sublime. To change your text editor, edit the `.git/config`. 
After opening your file in your text editor, add or make whatever changes you would like. CTRL + S saves the file, SHIFT + CTRL + W closes the Sublime file. Remember how to open files (described right above!).

___

[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
