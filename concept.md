#Git, GitHub, and Markdown: A Brief Conceptual Overview

## What is Git? 

**Git** is a version control tool. It lives on your computer (is local), and is accessed through the command line.  
![alt text][version_control]

[version_control]: https://github.com/jojokarlin/Git_DRI_Jan_2017/blob/master/images/version_control.png "Screenshot of different versions logged via git"  
Above, you can see different versions of the GCDRI's apply webpage over time. Starting from when Keith copied everything over from the repo for our old GCDRB (GC Digital Research Bootcamp) website, to fixing broken links, making stylistic tweaks, adding the new application form, and finally closing applications. Each version is logged here.

Git tracks changes when the user tells it to `git add` a file, and `git commit` logs the different versions you see here. When you `git add` and `git commit`, all these files live in the `.git` repository on your computer.

Git is the *local* power behind *version control*.

## What is GitHub?

**Github** is a hosting service for git repositories. You must first set up an account and configure it on your computer. Once your local **git** repository and a remote **GitHub** are connected, you can make copies of other users' repositories from GitHub, edit them, and send your proposed changes back to the GitHub repo so that the person who owns that repo can choose to incorporate your changes into their repository. 

Github _connects_ Git repositories remotely and is the power behind *collaboration*.

_If you have not signed up for a GitHub account, go to [http://github.com/](http://github.com/). Remember to save your user name, email, and password as you will need this information twice more!_

## What is Markdown?

Markdown is a markup language for formatting text. Unlike HTML, markdown is designed to be human-readable, which makes it much easier to write and edit.

You can think of markdown as a language read by many platforms and sites, including GitHub, to style text. Since markdown is plain text, it's also arguably more sustainable and accessible than formats like .docx. . You'll notice this file is in markdown--check out its extension!

To help you format your text (use markdown to translate plain to _pizzazz_), try this cheat-sheet: [GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). I used it as a reference to create this repo.  It is also appended to the bottom of the README.md file for quick access.

---

For more: [Dennis Tenen and Grant Wythoff, "Sustainable Authorship in Plain Text Using Pandoc and Markdown."](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)  

[<<< Command line](commandline.md) - [Configure Git >>>](gitconfig.md)  
[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md) 
