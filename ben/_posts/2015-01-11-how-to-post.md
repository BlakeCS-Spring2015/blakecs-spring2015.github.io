---
layout: post
title: "How to Post"
date: 2015-01-11 17:15:00
permalink: /how-to-post/
author: ben
tags: frontpage
---

and [Schmitty](/schmitty)

<br>

In order to make a new post, you will have to have GitHub for Mac set up with commit privilges to [the blog's repository](https://github.com/BlakeCS-Spring2015/blakecs-spring2015.github.io). You will need to learn a bit about Terminal to make a new post.

## Terminal Basics

Terminal is a direct interface with your computer. Instead of clicking through files, you are able to search through them with direct commands. In some ways, it's like going back to the way computers were used in the 70's.

In order to get around Terminal, you need to learn a few basic commands. When you open Terminal, it will say something like this:

    Last login: Thu Jan  8 21:40:16 on ttys000
    TBSLTMBA684:~ bmweinshel15$ 

Typing the command `pwd`, which stands for Print Working Directory, will (you guessed it) print the current folder that Terminal is open to.

    TBSLTMBA684:~ bmweinshel15$ pwd
    /Users/bmweinshel15

The command `ls` will list the files in the current directory (the default is the home folder):

    TBSLTMBA684:~ bmweinshel15$ ls
    Applications    Documents     Music       Public
    Desktop         Downloads     Library     Docs        
    Dropbox         Movies        Pictures

`cd`, or Change Directory, will change the folder that Terminal is looking at. Below I changed my working directory to `Docs` and listed the files:

    TBSLTMBA684:~ bmweinshel15$ cd Docs
    TBSLTMBA684:Docs bmweinshel15$ ls
    Git         Misc

## Create a New Blog Post

To create a new post, you start with a new Terminal window, and navigate to the blog folder. List the items in the folder, and `cd` to the `scripts` file. List the items, there should be a file called `new_post.rb`. Type `ruby` into a new line, followed by `new_post.rb`, and enter. Follow the prompts, and type your name as it appears on the blog. Then, go back into the Finder window, click on your posts folder, and there it is!

## Commit & Sync

As you make changes, they are all saved to the copy of the repository stored on your computer. Once you have the changes you need to make, you need to commit them to GitHub and synch for them to show up. To commit, go to the changes tab of GitHub for Mac, and under Uncommitted Changes, enter a quick summary of what you did. Click commit once you are satisfied. This saves the changes to your copy of the repository, and to update them to the blog, you have to press "Sync" in the top right corner.

## Markdown!

Essentially, markdown is a condensed version of html that is used for writing posts. It takes simpler commands, and when it's uploaded, translates that into html and THEN renders into a wonderful website. Instead of `<p>` tags on paragraphs, you just type, instead of `<h1-6>` tags, you just use # symbols. It also uses the spaces in the code itself to tell the website how to render the spacing.

More explanation available [here](http://blakecs-spring2015.github.io/schmitty/2015/01/05/markdown-cheatsheet/), in an earlier post on this blog. The original guide is [here](https://daringfireball.net/projects/markdown/basics), written by the creator.
