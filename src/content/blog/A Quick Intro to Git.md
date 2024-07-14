---
title: "A Quick Intro to Git"
description: "When I started learning how to code, I used to save my projects on a flash drive and in a backup hard-drive because my laptop often crashed due to my habit of experimenting with the operating system…"
pubDate: "Feb 23 2023"
heroImage: "/git_post_hero.webp"
tags: ["git", "github"]
---

When I started learning how to code, I used to save my projects on a flash drive and in a backup hard-drive because my laptop often crashed due to my habit of experimenting with the operating system. This meant I had to re-install Windows almost every month or so and lost my files and projects.

Then, I had no idea what Git or Github was all about until I came across a post that wrote about version control and this became a life saver (for my projects at least).

I want to use this medium to introduce you to Git and how it can add to your productivity.

## What is Git/Version Control?

Version control is a tool that helps you keep track of changes made to a set of files, such as a computer program or document.

It allows you to save different versions of the files, so you can easily go back and see how they looked in the past.

This is helpful for organizing and collaborating on projects, and also provides a safety net in case you make a mistake and need to revert to an earlier version.

## How To Use Git

First of all you need to have it installed in your pc. [Here is a link to download and install git.](https://git-scm.com/download/)

Having said that, lets get into the commands.

So basically there are three steps when it comes to using git:

1. Initializing the repository (Init);
2. Adding the file to git (Staging);
3. Commiting the changes to git (Commit).

Now lets see what they mean and their commands.

1. Initializing means to create the new git repository in the folder/directory that you are working on.

Here is the command:

```sh
git init
```

2. Staging simply means preparing the files to be stored in git repository.

Here is the command:

```sh
git add <your_file>
```

Note if you want to add multiple files you can simply list them.

For example

```sh
git add <your_file1> <your_file2> ...
```

If you want to add all the files in the current directory all you have to do it put a period instead of your file names.

```sh
git add .
```

3. Commit means to save the files/changes to git repository.

Here is the command

```sh
git commit -m "your commit message"
```

## Conclusion

There you have it, the three basic git commands.

Of course, there are more you can do with git but I didn't cover it here because this is a little introduction.

If you are interested in learning more about git [here is a manual provided by git official website](https://git-scm.com/book/en/v2).
