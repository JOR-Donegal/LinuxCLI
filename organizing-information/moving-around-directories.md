# Moving around directories

We will now examine how to move files around using these commands. Before starting, make sure you are in the \CLI directory!&#x20;

Examine these commands

**cp rubbish.txt rubbish1.txt**&#x20;

**cp rubbish.txt Backup**&#x20;

What was the difference in how the command was interpreted?

We can delete files in a directory which is not our working directory, using _relative paths_.

**rm Backup/rubbish1.txt**&#x20;

**cp ../rubbish.txt .**&#x20;

**ll**

What happened and why?

In many cases, (.) and (..) are very handy, however they do require you to know what your working directory is. One longer but safer option is to use absolute path names. Try using absolute pathnames to copy the file **rubbish.txt** to a backup directory
