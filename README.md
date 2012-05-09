# Purpose
This repo is intended to be used by the developers that wish to share and contribute to the reverse engineering of the GW2 DAT file and the contents within it.

I believe an open source effort will be the greatest way to achieve this. ArenaNet already knows of these efforts, and us posting releases with source on forums, means they already have access to the work we do.

# How This Works
The way this will be laid out, is each project will get a folder to put all their code in. This will eliminate messy branching and having to deal with teh massive merges. Second, it allows everyone to always see whats going on in one place.

Ex: Lets say you have a new GW2 DAT Unpacker, and you call it GW2Inflator. You would do something like this:

> /GW2Inflator
 . README
 . GW2Inflator.c
 . GW2Inflator.h
 . /lib

A README is required in every project folder with the following minimum:
Credits to everyone that worked on it. If you added something, add your name to the credits.
All compiling requirements. If your GUI uses WxWidgets, tells us that.

# Getting Access
There are 2 ways to do this. One is pull requests, where I don't believe I need to add you to the project, but you won't be able to directly commit to the tree, you will need to wait for someone to merge your pull request. But this allows you to not really need contributor access.

Second way is to get in contact with me, and ask me to be added as a contributor. This works fine, but I believe Pull Request method is the GitHub way, and many people prefer that.

# Notes
Please do not commit **binaries**, or user specific files generated by IDEs. You can inlude SLN files from Visual Studio, or the clean project files for another IDE, but try to clean it up and remove any files that are specific to your computer.