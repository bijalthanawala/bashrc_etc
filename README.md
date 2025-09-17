
# This repo is a bunch of useful config files

## One way to use the _.bashrc_ configuration in this repo is to follow these steps:
- Make a safe copy of your existing _~/.bashrc_ file
- Clone this repo
- Open your existing _~/.bashrc_ file in an editor and add this line at the end: ```source ~/bashrc_etc/bashrc_my``` or ```source ~/bashrc_etc/bashrc_my --verbose```
- The above line assumes that this repo was cloned in your home directory. Adjust the path in the above line if it was cloned eleswhere.


## One way to use the _.vimrc_ configuration in this repo is to follow these steps:
- Make a safe copy of your existing _~/.vimrc_ file
- Clone this repo
- Goto your home directory using this command:
```cd ~```
- Make a symbolic link to point __~/.vimrc__ to this repository's __.vimrc__ using this command: ```ln -s ~/bashrc_etc/vimrc .vimrc ```
- The above line assumes that this repo was cloned in your home directory. Adjust the path in the above line if it was cloned eleswhere.
