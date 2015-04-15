This utility provides an enhanced command history for Bash, keeping track of all commands ever entered in any terminal window as well as the directory in which the command was entered.

PREREQUISITES

This script currently only works with Bash.  A modified version that works with zsh will be uploaded soon.
The script makes use of xmlstarlet, which can be downloaded from http://xmlstar.sourceforge.net.

INSTALLATION

1.  Copy the .bash-capture script to your home directory.

2.  Copy the empty .command.log file to your home directory.

3.  Add a "source bash-capture" line to the bottom of your .profile or .bashrc file.
