# Git newbee manual by @Selge.


Well, this is just a short GIT-newbee manual. 

## Git basics:

How to start working with Git? First you need to create a Git account on one of Git web services: GitHub, GitLab etc. 
For the moment GitHub is the world's most popular Git service and I do recommend to start using it if you're a git-beginner. GitHub has its own Wiki, proposes a lot of additional services and features, it's easy to use and enjoy. To create an account please visit: https://github.com/
aaaand you should see this page:

![GitHub start page](img/GitHub%20start%20page.png)

_GitHub start page_

## Git installation:

First make sure you've created a Git account (please look above for help).
After creating an account, download and install required Git version please follow the link:

https://git-scm.com/

![Git download page](img/Git%20download%20page.png)

_Git officlial page_

From my point of view it's much more useful for a programmer to use GitBash shell, but you may as well try one of Git GUI (graphical user interface) desktop apps.


You may use standart desktop Git GUI application:

![This is how standart Git GUI window looks like](img/Git%20GUI.png)

_Git GUI window_


But if you surely want to use GUI application, I do recommend GitHub desktop:

![This is how GitHub desktop GUI looks like](img/GitHub%20desktop%20GUI.png)

_Github desktop window_


If you use the GitBash (as I recommend) just start the GitBash.app and just type the commands in the window:

![A standart GitBash window](img/GitBash.png)

_GitBash shell window_

## Git commands:

***First let's check if Git is installed:***

**git --version** - shows (if Git is installed to your OS) current program version

***Then let's introduce yourself to Git:***

**git config --global user.name "Username Usersurname"** - Your Name

**git config --global user.email "username@isegal.de"** - Your e-mail address

***After that use the commang you currently need:***

**E:/Whatever/TestGitFolder/Whatever_2 git init** - creating a new repository from an any existing directory

**git status** - checking current git repository status (checks if files in your local project are updated with the target repository)

**git add** - adding file/files to the next commit

**git commit -m "message"** - creating new commit. "message" is adding a small comment so you understand what's changed

**git log** - showing commit history

**git checkout** - swap to the next commit

**git checkout master** - stop commiting, go back to work!

**git diff** - showing difference between actual and commited file/files

## Git in daily use:

**git clone <here we get URL of the required repository** - cloning ***all*** the repository, including all the existing branches *and the same time trying to merge all of them*


### What is Git branches about?
![How do the git branches work](img/git-branches-merge.png)

_Git branch system was designed to test different options on the same code snippets or to merge together different files to craft the final product._

**git pull** - 

**git push** - 

**pull request** - 

### Thank you for your attention!
![Thanks for reading](img/ThanksForReading.jpg)