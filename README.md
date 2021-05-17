# dmenu - dynamic menu
dmenu is an efficient dynamic menu for X.

## Patches included
* dmenu-fuzzymatch-4.9
* dmenu-lineheight-4.9
* dmenu-numbers-4.9
* dmenu-password-4.9

## Screenshots
<img src="Screenshots/Screenshot_from_2021-05-17_19:39:26.png" width=1000px>

## Requirements
In order to build dmenu you need the Xlib header files.

## Installation
Edit `config.mk` to match your local setup (dmenu is installed into
the `/usr/local` namespace by default).
Afterwards enter the following command to build and install dmenu
(if necessary as root):
    `make clean install`

## Running dmenu
See the man page for details.
