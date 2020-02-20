# .saferm
Wrapper to prevent tragedies caused by `rm`. Intended to be aliased over `rm` so that you only use the built-in (unsafe) tool when you truly need the extra functionality. Works on files and directories.

# Disclaimers
* Developed on Ubuntu 18.04, should work with all Unix-based systems but untested.
* `~/.Trash` will need to be manually emptied at this point in development.

# Installation
1. Clone repo and put `.saferm` file in `/usr/bin` or another executable location.
1. Make `.saferm` executable.
1. Edit `~/.bash_aliases` file to include the line `alias rm="\path\to\.saferm"`. 
1. Make sure `.bashrc` sources `.bash_aliases`.
1. `source .bashrc` 

Voila, `.saferm` should be up and running.
