# Moving Files

**mv** \[_file1_] \[_file2_] moves (or renames) _file1_ to _file2_

To move a file from one place to another, use the mv command. This has the effect of moving rather than copying the file, so you end up with only one file rather than two. It can also be used to rename a file, by moving the file to the same directory, but giving it a different name. We are now going to move the file _file1.bak_ to your _backup_ directory.

First, change working directory to your _Exercise1_ directory (can you remember how?). Check the contents!

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Then, inside the _Exercise1_ directory, type

```
mv file1.bak backups/
```

Type **ls** and **ls backups** to see if it has worked.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>
