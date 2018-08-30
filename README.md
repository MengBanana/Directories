# Directories

This program is a set of C functions that perform specified operations 
on files and directories that require using information about files, 
directories and directory entries.

Given a filename and a directory path, this program is able to count the
number of directories under a certain directory, find out the size of a 
regular file, and count the total size of all regular files under a certain
directory. The main concept is to iteratively check all names under the
directory, and using state mode to determine if it is a regular file or
directory.

It also check if two names refer to the same file or directory by
comparing inode.
