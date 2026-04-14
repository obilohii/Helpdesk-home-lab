# Day 3 - Linux Users and Permissions

Today I practiced Linux permissions and user-related concepts in the terminal. The goal was to better understand how access works for files and folders, how to change permissions, and how to verify whether those changes worked.

## Tasks Completed
- Practiced reading Linux permission strings
- Learned how permissions apply to owner, group, and others
- Used `chmod` to change file and folder permissions
- Checked permissions using `ls -l`
- Thought through user-related errors and what they mean
- Verified whether a folder allowed full access to everyone

## Lab Summary
For this lab, I focused on understanding how Linux controls access to files and directories. I learned that permissions are split into three groups: the owner, the group, and others. Each of those groups can be assigned read, write, and execute permissions.

I practiced using `chmod` to change permissions on a folder and used `ls -l` to verify the results. I also learned that folder permissions behave a little differently than file permissions, especially when it comes to the execute permission. In a directory, execute permission allows a user to enter or access that folder.

## What I Practiced
I worked on reading permission strings such as `drwxrwxrwx` and understanding what each character means. I also practiced using `chmod 777 newuserfolder` to give full permissions to the owner, group, and others.

To confirm the changes, I used `ls -l` to check the updated permissions and verify that the folder was set the way I expected.

## Mistake / Question I Ran Into
One thing I ran into was confusion around a fatal error when trying to add a new user. I learned that a fatal error usually means the command failed because of something important, like incorrect syntax, missing privileges, or trying to create a user that already exists.

That reminded me that reading terminal output carefully is important because the system is usually telling me exactly what went wrong.

## Commands Practiced
- `chmod`
- `ls -l`

## What I Learned
This lab helped me better understand:
- Linux permissions are divided into **owner**, **group**, and **others**
- `r` means read, `w` means write, and `x` means execute
- `chmod` is used to change permissions
- `ls -l` is useful for checking whether permission changes worked
- execute permission on folders allows access into the directory

A big takeaway from today was:
- `drwxrwxrwx` means everyone has read, write, and execute permissions
- `chmod 777` gives full access to everyone
- permissions are a major part of Linux security and access control

## Reflection
Day 3 helped me slow down and actually understand what Linux permissions mean instead of just memorizing commands. It made me realize how important permissions are for security and for controlling access to files and folders. I feel more confident now reading permission strings and checking whether my commands worked correctly.