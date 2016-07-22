# Lab 01 -- Getting started with Git

In this lab we will be introduced to delivery method of all labs, daily assignments, and projects. This method will rely on learning `git`. According to [Wikipedia](https://en.wikipedia.org/wiki/Git_(software)), "Git (/ɡɪt/) is a version control system that is used for software development and other version control tasks. As a distributed revision control system it is aimed at speed, data integrity, and support for distributed, non-linear workflows." Basically, it is a more sophisticated Dropbox and allows you to keep your code up to date across multiple platforms. 

Follow the instructions below to complete the lab.

## Sign up with GitHub

If you don't already have an account, you will need a GitHub account. You can do so here: [https://github.com/](https://github.com/). 

## Cloning and Forking a Repo

First, what is a repo and why would you want to do these things to it? __Repo__ is short for repository which is basically a directory of files and folders. Think of your GitHub account as a large folder containing other folders (repos). Each repo is a different project, or in this case, lab. If you just created a GitHub account, then you don't have any repos yet. We are going to change that.

This is where forking comes in. You need to copy the `lab01` repo into your account. This way you can edit/add files. A __Fork__ of a repo is like a fork in a road. There is a main road (the original `lab01` repo) and a fork off the road (your repo). At any time you are editing the forked repo (or traveling the forked road), you can go back to the original.  

Forking the a repo is super easy. All you need to do is click the fork button at the top of this page ([https://github.com/csc-171/lab01](https://github.com/csc-171/lab01)) and select the account to fork to. __Do this now.__

Bam! You have forked a repo! Congratulations. 

__From now on, this is the first thing you should do when you start a lab in this class.__

So now what? You have a forked repo sitting on some server. How do you get your hands on it? Well you could use the GitHub interface, but that is lame. So we need to get the files to your local machine. There are several ways to do this, but the cool kids like to clone. __Cloning__ is just copying and pasting the repo to your local machine. To do this we need to get our hands a little dirty with the following steps.

1. Open `Git Bash` on your machine. This is a command line interface that allows you to communicate with GitHub.
2. Look for a green button on this page that says `Clone or download`, click it, and copy the text. It should look something like this: `https://github.com/csc-171/lab01.git`. 
3. Go back to Git Bash and enter the following (note, don't enter the `$`, it's just there to tell you that is the start of the line):
```
$ git clone https://github.com/csc-171/lab01.git
```
4. Next change directory to the repo by typing:
```
$ cd lab01
```
5. Look into the repo by typing:
```
$ ls
```

You see? All of the files are there! This is great right? Now you have a local copy of the repo sitting on your machine. No matter what you do, you will not mess up the originals. All of your edits/changes will be local on your machine until you push your changes back to the server. So let's do that.

## Why should I care about `Git`?

* version control
* helps keep track of conflicts on collaborative projects
* Complete history
* 



## Adding Files

```
$ git add

## Committing Changes

## Pushing (Pushing up local changes to server)

## Pulling (Pulling down server info to local machine)

## Pull Request (Submitting Lab Assignments)




