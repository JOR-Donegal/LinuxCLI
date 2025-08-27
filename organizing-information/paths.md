# Paths

You will recall that in either Unix or DOS

(.) means the current directory, so typing cd . means stay where you are.&#x20;

(..) means the parent of the current directory, so typing cd .. will take you one directory up the hierarchy.&#x20;

We have used the term _working directory_ previously to describe the current working directory the shell is operating in.&#x20;

In Linux we can use the command **pwd** to show our working directory

Before we type a command, we really need to know what our current directory is. We have several types of paths and I will briefly explain them now. An _absolute path_ is the path to a file with respect to the root. If I want to delete a file deep in my directory structure, I can type&#x20;

**del /home/john.oraw/CLI/rubbish.txt**&#x20;

and regardless of which working directory I am in, this will work.&#x20;

I can also delete a file using a path _relative_ to my working directory. Suppose I have a working directory of&#x20;

**/home/john.oraw/CLI**&#x20;

and I want to delete the same file as above. I could type&#x20;

**del ./CLI/rubbish.txt**&#x20;

and this would still work.
