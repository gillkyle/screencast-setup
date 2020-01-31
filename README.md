When recording the command line, it’s important to have a consistent application style. The main Tutorial has some nice examples of how to render an application over a background color.
 TODO: more details needed here, including a reusable profile.

The terms terminal and shell are often used somewhat interchangeably. The shell is a program which processes commands and returns output. Examples of a shells are:
bash (popular on Linux)
zsh (default for Mac)
cmd (used on Windows)
PowerShell (also Windows)
The terminal is a program that runs a shell and runs as an application on your machine. Examples of terminals are:
Terminal (native to Mac)
Command Prompt (native to Windows)
iTerm2 (Mac only)
Hyper (Cross-platform)
The Shell
Most shells share common commands and setup so any shell should be okay for recording screencast. 

However, the Windows shell has many differences from the most common workflows for web development, so the Windows Subsystem for Linux is recommended to be able to run unix-like commands (much like Linux and Mac) if you are on Windows. 

Setting up your Terminal
For screencasting, you should install either iTerm2 or Hyper. Both can be customized to remove extraneous information and identically styled profiles for each one are linked in this doc.

These screenshots show what each looks like when set up:

iTerm2:
Hyper:


Installation


https://www.iterm2.com/downloads.html
https://github.com/zeit/hyper#usage
Using a profile
To keep styles consistent, you can import a customized profile saved under a name that can be accessed for when you are recording screencasts
Import the “Screencast” profile:
Profiles > Open Profiles > Edit Profiles > click other actions > Import JSON Profiles > choose this JSON file after downloading




Install this plugin for using profiles:
https://github.com/chabou/hyper-autoprofile




The following styles are used in each respective terminal profile:
Font-size: 20px
background-color: #000
Font-color: #fff
Font: Menlo







