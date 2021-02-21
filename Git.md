# Git Tutorial: A Comprehensive Guide
what is Git?


Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

How can we download Git ?
In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.

Git can be installed in three ways:

Install as a package
Install via another installer
Download and compile the source code.

# Identity Setting

After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.

Type the following into Terminal or Command Line:

git config --global user.name "Jane Smith"

git config --global user.email "example@email.com"
To confirm that you have the correct settings, enter the following command:

git config --global user.name (should return Jane Smith)

git config --global user.email (should return example@email.com)

# Importing
To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

Switch to the target project’s directory
Example:

$ cd test (cd = change directory)
Use the git init command
$ git init
Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

To start tracking these repository files, perform an initial commit by typing the following:
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here” 
# Cloning
You can also create a copy of an existing Git repository from a particular server by using the clone command.



