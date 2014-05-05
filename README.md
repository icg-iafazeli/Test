Testing Git
====

$ mkdir ~/Test
# Creates a directory for your project called "Test" in your user directory

$ cd ~/Test
# Changes the current working directory to your newly created directory

$ git init
# Sets up the necessary Git files
# Initialized empty Git repository in /Users/you/Test/.git/

$ touch README
# Creates a file called "README" in your Test directory


$ git add README
# Stages your README file, adding it to the list of files to be committed

$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"
