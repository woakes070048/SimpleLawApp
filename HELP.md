# How to Set Up Workspace for Development

This serves as a tutorial to help members of the SimpleLaw team set up an appropriate development environment. It is not written with anyone else in mind.

## 0. Create a GitHub Account

If you don't have one already, [create a GitHub account](https://github.com/join). You must then tell me (Matthew Huggins) your username so that I can grant you access to the SimpleLawApp repository. Be sure to accept the request to join SimpleLaw.

## 1. Set up GitHub on your PC

We will be using [GitHub](https://github.com/) to organize our collaborative work on the new version of SimpleLaw.org. If you are very comfortable using the command line, or work on a Linux machine, you can [install the command line tools](https://help.github.com/articles/set-up-git/). *Be aware that this tutorial will not cover using the command line tools.* If you are using a Windows or Mac machine, **I would highly recommend using either [GitHub for Mac](https://mac.github.com/) or [GitHub for Windows](https://windows.github.com/)**. These are GUI-based clients that make things quite easy.

## 2. Clone the SimpleLawApp Repository

If you have been added to the SimpleLaw team (i.e. you've given me your username and accepted the request to join), you will be able to start working.

First, you will need to clone the SimpleLawApp repository. Either click on the "Clone in Desktop" link on the [repository page](https://github.com/SimpleLaw/SimpleLawApp), or in your GitHub desktop application click on the plus sign in the top left corner, choose clone and then select the SimpleLawApp repository. You will be able to choose where in your machine's filesystem the repository is stored.

## 3. Install Meteor

Meteor is an open-source web application development platform which allows us to quickly and cleanly build the new SimpleLaw. If you are using a Windows machine, [download the installer](https://install.meteor.com/windows). If you use a Mac or Linux machine, open the Terminal and execute the following command:

'curl https://install.meteor.com/ | sh'

## 4. Install a Good IDE/Editor

While you could edit source code in your PC's native text editor, you should use something better. There are many options, but here are a few I would recommend:

* [Atom](http://atom.io/) (My choice)
* [Sublime](http://www.sublimetext.com/)
* [Vim](http://www.vim.org/)
* [Xcode](https://developer.apple.com/xcode/) (Mac Only)

## 5. Start the Meteor Server

Open up the Terminal and navigate to the Simple_Law folder in the SimpleLawApp repository directory.