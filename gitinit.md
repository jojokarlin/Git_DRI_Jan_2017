# Initialize Git

Using `cd`, navigate inside the folder 'GitPractice.' 

Type `git init` and hit enter.

This initializes the Git repository so it knows to pay attention to this folder. 

You should see something like `Initialized empty Git repository in /Users/gcdri/Desktop/GitPractice/.git/`

### Create a file in your folder.  

We are going to make our own cheatsheet as a plain text markdown file.

Make sure you're navigated inside your GitPractice folder. Use `cd` or `cd ..` as needed.

Type `touch gitcheat.md` The '.md' extension means "markdown." You can use `touch` to create other types of files too: `touch [name].[extension]`.

### Start your file.

`open gitcheat.md` will let you get started.

Whatever text editor pops up should be the one that you set in your `git config`. We have configured it to use Sublime. If Sublime still won't automatically pop up, try `subl gitcheat.md` or just go ahead and open it in Sublime using your GUI.

Using **markdown style**, give your document a title, insert your name and today's date. For reference, here is the [GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) again. 

![alt text][gitcheat start]

[gitcheat start]: https://github.com/jentang/GitDRI/blob/master/gitcheat%20start.png "How the start of your git cheatsheet might look inn sublime"
CTRL + S saves the file, SHIFT + CTRL + W closes the Sublime file.  
___

[<<< Configure Git](gitconfig.md) - [Connect to GitHub >>>](github.md)  
[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
