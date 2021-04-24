# Git-github-markdown

# Command Line

In the first part we are going to learn ways to improve our velocity when we are using the computer with this command line sheets.


## Directories

`mkdir [Directory Name]`
__mkdir__ is the abreviation for make directory, to use it correctly we only need to type this followed by the directory name.

`rmdir [Directory Name]`
__rmdir__ is the abreviation for remove directory, to use it correctly we only need to type this followed by the directory name.


## Navigate

`cd`
We can use __cd__ followed by the route we want to go to move throghout the directories. 


## Compare

`cmp`
It is used to compare the two files byte by byte and helps you to find out whether the two files are identical or not.


## Find files

`find [Route] [Name or extension]`
This is kind of difficult to explain so we have this example:
__find /home/example-username/ -filename_example__


## Create and edit files

`nano`
There are a lot of ways to create and edit a file but here we have nano because as my way to see, is the easiest, just type nano followed by the name of the file we want to create or edit.


##Get the state of computer

`lscpu`
At least in Linux, which is the operating system I use, this command is useful to see the state of the computer.


# Git Commands

In this part, you can find some of the most important commands or cheats that exists in git.


## Configuration

Obviously, we need to set up our environment in which we are going to work. For this, git provides us some cheats to set default values. For example:

`$ git config --global user.name "Your name"` 
This set us the name that will be attached tp our commits and tags.

`$ git config --global user.email "Your email"`
It is like the previous one, just that is our email, not our name (It shows in commits and tags).
