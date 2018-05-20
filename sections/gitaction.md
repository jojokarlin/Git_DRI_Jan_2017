[<<< Previous](markdown.md) | [Next >>>](github.md)

# Staging and Committing Changes

Git's primary function is to track a project as it exists at different points in time. Now that we have a file to track—our markdown syllabus—let's use Git to save the current state of the repository as it exists now.

## A Metaphor for Adding and Committing

In Git, a **commit** is a snapshot of a repository that is entered into its permanent history. To commit a change to a repository, we take two steps:

1. Adding files to a "staging area," meaning that we intend to commit them.
2. Finalizing the commit.

Making a commit is a lot like taking a photo. First, you have to decide who will be in the photo and arrange your friends or family in front of the camera. Once everyone is present and ready, you take the picture, entering that moment into the permanent record.

## Staging Changes with the Add Command

First, let's use a useful command to see what state Git is currently in. It's a good idea to use this command before and after doing anything in Git so you can always be on the same page as the computer.

Make sure you're in your `/home/<your-name>/Desktop/projects/git` directory using the `pwd` command in the terminal. Once you're there, enter this command:

	git status
	
You should see output like this:

```
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	syllabus.md

nothing added to commit but untracked files present (use "git add" to track)
```

This means we've initialized our repository, but haven't made any commits yet. If you're instead get a message that begins with the word `fatal` when you use `git status`, you may be in the wrong directory or haven't run the `git init` command on your directory yet.

Let's follow the recommendation in the status message above and use the `add` command to stage files, making them ready to be committed.

Type this command:

	git add syllabus.md
	
You should see no output from the command line, meaning that the above command succeeded. Let's run `git status` again to check if things have changed. You should see output like this:

```
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   syllabus.md
```

The `new file:   syllabus.md` should be highlighted in green to show that it's ready for commit.

## Committing Changes

Now that our files have been staged, let's commit them, making them part of the permanent record of the repository. Type:

	git commit -m "Initial commit of syllabus file"
	
The `-m` flag provides a message along with the commit that will tell others—or remind a future version of yourself—what the commit was all about. Try not to type `git commit` without the `-m` flag for now—there's a note about this below.

After running the command, you should see output like this:

```
[master (root-commit) 8bb8306] Initial commit of syllabus file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 syllabus.md
```

This means you have successfully made your first commit in the repository—congratulations!

Let's check the state of our repository after the commit with `git status`:

```
On branch master
nothing to commit, working tree clean
```

This means that everything in the repository is successfully committed and up-to-date. If you edit your syllabus file or create a new file in the repository., the message you get with `git status` will instead list files that have uncommitted changes.

Let's run one other command to see the effect our commit has had. Enter this command:

	git log
	
You should see output similar to this:

```
commit 8bb8306c1392eed52d4407eb16867a49b49a46ac (HEAD -> master)
Author: Patrick Smyth <patricksmyth01@gmail.com>
Date:   Sun May 20 16:03:39 2018 -0400

    Initial commit of syllabus file
```

This is the log of commits, comprising a history of your repository. There's only one commit here now, though. If you don't see a prompt (the `$`) after running `git log`, you may need to press the `q` key (just the `q` key by itself) to return to the command line.

## Optional: Why Do We Need to Use the -m Flag?

If you type `git commit` by itself, git will open the command line's default text editor to allow you to enter the commit message. Unfortunately, the default text editor, `vi`, requires some knowledge to use, and we don't teach it as part of our sessions.

If you find yourself stuck in an unfamiliar screen in the command line after running `git commit`, you're probably in `vi`. Type this to leave that environment and return to the `$` prompt:

	:q
	
If you're ever stuck or "trapped" on the command line, try running through these common exit commands to return to the prompt:

```
Control-c
Control-d
q
:q
```

`Control-c` attempts to abort the current task and restore user control. `Control-d` escapes the current shell environment—if you use it at the normal `$` prompt, it will end the current command line session. `q` is used to escape from specific utilities like `less`. `:q` first changes the mode in `vi`, allowing you to enter the `q` key to quit, so it's a command specific to `vi`.

[<<< Previous](markdown.md) | [Next >>>](github.md)

