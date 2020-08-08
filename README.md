[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# Getting Started with Open Source

This repository aims to give an introduction as to how the Open Source World functions.
Use this project to make your first contribution to an open-source project on GitHub. Practice making your first pull request to a public repository before doing the real thing!


This repository is open to all  members of the GitHub community. Any member can contribute to this project without being a collaborator.

Repo Link : [https://github.com/AdityaRajSingh/Git](https://github.com/AdityaRajSingh/Git)


## Choose from these tasks 

Here are 3 quick and easy ways to contribute to this project:

* Task-1: [Add your name and description](https://github.com/AdityaRajSingh/Git/tree/master/Task1)
Add your name to the website with description and make your way to Open Source.

* Task-2: [Making your Own portfolio page](https://github.com/AdityaRajSingh/Git/tree/master/Task2) 
Host your very own portfolio page in minutes and share with us to get nearer to swags

* Task-3: [Show Off coding skills](https://github.com/AdityaRajSingh/Git/tree/master/Task3)
Help us in making a one-stop place to find necessary codes and articles, which can vary from `Hello World` to `Dynamic Programming` in any language of your choice.  

Choose one or all 3, make a pull request for your work and wait for it to be merged!


## Steps to follow :scroll:

### 0. Star The Repo :star2:

Star the repo by pressing the topmost-right button to start your wonderful journey.


### 1. Fork it :fork_and_knife:

You can get your own fork/copy of [Git](https://github.com/AdityaRajSingh/Git) by using the <a href="https://github.com/AdityaRajSingh/Git/new/master?readme=1#fork-destination-box"><kbd><b>Fork</b></kbd></a> button or clicking [this](https://github.com/AdityaRajSingh/Git/new/master?readme=1#fork-destination-box) at top-right of your screen.

 [![Fork Button](https://help.github.com/assets/images/help/repository/fork_button.jpg)](https://github.com/AdityaRajSingh/Git/)


### 2. Clone it :busts_in_silhouette:

`NOTE: commands are to be executed on Linux, Mac, and Windows(using Powershell)`

You need to clone (download) it to local machine using

```sh
$ git clone https://github.com/Your_Username/Git.git
```

> This makes a local copy of the repository in your machine.

Once you have cloned the `Git` repository in Github, move to that folder first using change directory command on Linux, Mac, and Windows(PowerShell to be used).

```sh
# This will change directory to a folder Git
$ cd Git
```

Move to this folder for all other commands.

### 3. Set it up :arrow_up:

Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:

```sh
$ git remote -v
origin  https://github.com/Your_Username/Git.git (fetch)
origin  https://github.com/Your_Username/Git.git (push)
```

Now, let's add a reference to the original [Git](https://github.com/AdityaRajSingh/Git/) repository using

```sh
$ git remote add upstream https://github.com/AdityaRajSingh/Git.git
```

> This adds a new remote named ***upstream***.

See the changes using

```sh
$ git remote -v
origin    https://github.com/Your_Username/Git.git (fetch)
origin    https://github.com/Your_Username/Git.git (push)
upstream  https://github.com/Remote_Username/Git.git (fetch)
upstream  https://github.com/Remote_Username/Git.git (push)
```
`In your case, you will see`
```sh
$ git remote -V
origin    https://github.com/Your_Username/Git.git (fetch)
origin    https://github.com/Your_Username/Git.git (push)
upstream  https://github.com/AdityaRajSingh/Git.git (fetch)
upstream  https://github.com/AdityaRajSingh/Git.git (push)
```

### 4. Sync it :recycle:

Always keep your local copy of the repository updated with the original repository.
Before making any changes and/or in an appropriate interval, run the following commands *carefully* to update your local repository.

```sh
# Switch to `master` branch
$ git checkout master

# sync our local copy with the `upstream` repository  & Push changes to your forked `Git` repo
$ git pull upstream master && git push origin master
```

### 5. Ready Steady Go... :turtle: :rabbit2:

Once you have completed these steps, you are ready to start contributing by checking our `Help Wanted` Issues and creating [pull requests](https://github.com/AdityaRajSingh/Git/pulls).

### 6. Create a new branch :bangbang:

Whenever you are going to contribute. Please create a separate branch using command and keep your `master` branch clean (i.e. synced with remote branch).

```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b BranchName
```

Create a separate branch for contribution and try to use the same name of the branch as of folder.

To switch to the desired branch

```sh
# To switch from one folder to other
$ git checkout BranchName
```

To add the changes to the branch. Use

```sh
# To add all files to branch Folder_Name
$ git add .
```

Type in a message relevant for the code reviewer using

```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```

Now, Push your awesome work to your remote repository using

```sh
# To push your work to your remote repository
$ git push -u origin BranchName
```

Finally, go to your repository in the browser and click on `compare and pull requests`.
Then add a title and description to your pull request that explains your precious effort.


## Help Contributing Guides :crown:

We love to have `articles` and `codes` in different languages and the `betterment` of existing ones.

Please discuss it with us first by creating a new issue.

:tada: :confetti_ball: :smiley: _**Happy Contributing**_ :smiley: :confetti_ball: :tada:

## Code Maintainer:
The project is maintained by :
 - [Aditya Raj Singh](https://github.com/AdityaRajSingh)

