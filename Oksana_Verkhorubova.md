# **GIT users manual**
## _**Start using of GIT**_
GIT is a programm for control of versions that is commonly used in IT sphere.

First of all, user shoud install GIT and the text editor Visual Studio code (VS code).

* For downloading GIT use link:  https://git-scm.com/downloads

* For downloading VS code use link:  https://code.visualstudio.com/Download

In the first using of GIT the user should register in GITHub and enter **email** and **login** in terminal.


## _**Main commands in GIT**_
* git init – initialization of local repository
* git status – getting information from git about its current status
* git add – add file(-s) to the next commit
* git commit -m “message” – making a commit
* git log – display history of all commits with hash codes
* git checkout – changing to another commit
* git checkout master – return to relevant status and continue working
* git diff – show difference between current and commited files

## _**Syntax of Markdown**_
Markdown is a lightweight markup language that can be used to add formatting elements to plaintext text documents.

The main rules of formatting text are listed below:
1. The symbol # is used for highlighting headings. Number of # sets the level of the heading (up to 6 levels)
2. = or - underline by these symbols (not less than 3) highlights headings of the first (“=”) and the second (“-”) levels
3. For **Bold inscription** or __Bold inscription__ use ** or __ in the beginning and in the end of the text 
4. For *Italic inscription* or _Italic inscription_ use * or _ in the beginning and in the end of the text 
5. For ***Bold italic inscription*** use *** in the beginning and in the end of the text 
6. For ~~Crossed out text~~ use ~~ in the beginning and in the end of the text 
7. * element – non-numerical lists, symbol “*” in the beginning of the line
8. 1, 2, 3 … – numerical lists

## _**Working with branches**_
In order to have a possibility to work with different versions (drafts) of document or to work with a document in a group of people simultaneously in GIT branches are used.

* To create a new branch use a command **git branch new_branch_name**.

* To display in which branch user is working enter command **git branch**.

* To switch between initial (master) branch and another branches use a command **git checkout new_branch_name**.

* To delete branch enter a command **git branch -d branch_name**.

To display commits as a tree use a command **git log --graph**.

In case of conflicts while merging branches (different information added in the same place) user can change 1 of possible decisions:
* accept changes made in current branch
* accept changes made in merging branch
* accept both changes
* compare changes

## _**Working with pictures**_
To add a picture into text user needs to:
1. save a picture into a repository folder
2. use a command **git ignore**
3. add into text ![description/comment](fail name)

## _**Working in remote repository**_

Remote repositories can be made on the most popular service of GIT - GitHub. Working in remote repository allows to work with file by several users simultaneously. Main commands for exchanging repositories to and from GitHub are listed below:

* git clone <url-adress of repository> – cloning of external repository on local PC
* git pull – getting changes and merging with local version
* git push – sends local version of repository to external source

### _How to work in|with remote repository:_
1. Authorize in GitHub
2. Go by the link on external repository in GitHub
3. Press on the **Fork** button of external repository - this repository will appear in the list of user's repositories
4. Clone it into user's local PC
5. Open cloned folder in VS code
6. Enter **git branch new_branch_name**
7. Switch into new branch by **git checkout new_branch_name**
8. Add new file, make a commit
9. Enter **git push** (in case of an error enter a command from prompts)
10. Enter **pull request**