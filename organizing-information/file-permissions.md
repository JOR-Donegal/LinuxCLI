# File Permissions

**cp&#x20;**_**file1 file2**_ is the command which makes a copy of _file1_ in the current working directory and calls it _file2_.

We are going to create a file called _File1.txt_ in your home directory, and use the **cp** command to copy it to your _Exercise1_ directory.

First, change to your home directory using the command

```
cd ~
```

then use the **cat** command to create the _file1.txt_ file with some contents. Type the lines exactly as I have, including case and punctuation. To start, type;

```
cat > file1.txt
```

When you are finished, press

**\[ctrl]\[d]**

to save and exit.

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

The quote is from “As you like it”, Shakespeare!

Now, change your working directory to your _Exercise1_ directory,

```
cd ~/Exercise1
```

then copy the file you just created (\~_/file1.txt_) to the Exercise1 directory by typing the command;

```
/cp ~/file1.txt .
```

Be careful, the format of the command is **cp** \[_source_] \[_destination_]

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

Look at the example above, it copies the source “_\~/File1.txt_” to the destination “.”

Don't forget the dot at the end! Remember, in Linux, the dot means the current directory.

The above command means copy the file _File1.txt_ to the current directory, keeping the name the same. Do a **ls** or **ll** to check that this worked.

## Exercise

In your _\~/Exercise1_ directory, create a backup of your _file1.txt_ file by copying it to a file called _file1.bak_

Then delete the _file1.txt_ file in your home directory (not the one in the _Exercise1_ directory).
