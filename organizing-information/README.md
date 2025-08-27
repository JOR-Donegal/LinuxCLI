---
description: Files and Directories
---

# Organizing Information

The primary unit of storage which you will interact with is a _file_. A file may be a document, a programme, a list of settings etc. Each file has a name and may have other attributes defined relating to it.&#x20;

Files are stored in _directories_ to make organization a little easier. These are the same as the folders you use in Windows.

Directories may be _nested_, this means you can have directories within directories.&#x20;

The top of each file system is called _root_, normally designated by "\\" in Windows and "/" in Unix.&#x20;

In DOS and Windows, each physical disk is addressed separately and has a separate root. A disk is normally abstracted as a letter followed by the colon symbol. Original Microsoft systems had two floppy disk drives, the first floppy disk drive was normally A:\ the second was B:\ and when hard drives came along, the first hard drive was C:\\. On a modern PC, the operating system is always installed on the C:\ drive, because historically it was the first hard drive. If installed, the CDROM/DVD player is normally D:

On a networked computer, many other drive letters may exist, normally referring to shared folders on servers (which are abstracted to the computer and user as if they were internal hard drives). In the university, you are allocated a Cloud share. You will always see it as&#x20;

In Windows, the default command prompt shows you the working directory you are in. For example, C:\Users\Your.Name. If you are working on a home computer and cannot see you path at the command prompt, type **prompt $p$g** followed by return. Alternatively, type **cd** to find the working directory.&#x20;

In Unix, each physical disk or resource is grafted to the file system and there is only one file system. The physical disk will not appear separately, and all storage appears part of the one file system. In Unix, we type **pwd** to get the name of the working directory.&#x20;

In Linux, all users have a home directory, normally under the **/home** directory. Make sure you know what your home directory is before you continue.
