# trsh
A Trash Utility for GNU/Linux

# Why?
No reason. Just made it for fun. It works fine, but it is up to you if you want to use it.

## Functions

General Usage: *trsh [filename]*

More than one file can be listed:

*trsh [filename] [filename] [directory] [filename].zip ../.[directory]*


Help Command: *trsh -h*


Empty Trash: *trsh -e*


Changes the Trash Directories: *trsh -d*

## Trash locations
Default trash locations for files and info:

Files: `/home/$USER/.local/share/Trash/files`

Info: `/home/$USER/.local/share/Trash/info`

These locations can be changed with *trsh -d*

## Install
`git clone https://github.com/paperblock01/trsh.git`

`cd trsh`

`chmod +x trsh`

To use `trsh` as a universal command:

(Requires root permissions)

`chmod a+x trsh`

`sudo cp trsh /usr/bin`

## Known Problems

