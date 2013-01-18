Apple wired keyboard configuration with Hungarian layout
========================================================

This repository contains configuration files for the wired Apple keyboard with Hungarian layout.

Usage on Linux:
---------------
- Copy the linux/.Xmodmap file to ~/.Xmodmap.
- Logout or restart.

If you want F1, F2, etc... keys to behave as F keys, configure the "fn" button (works on Ubuntu 12.10):
    $ echo 2 | sudo tee /sys/module/hid_apple/parameters/fnmode


Usage on Windows:
-----------------
- Install the free and open source Autohotkey application from http://www.autohotkey.com/.
- Copy the win/autohotkey_wired_apple_keyboard_hu.ahk file to a safe place. 
- Create a shortcut to that file, and copy the shortcut to the Startup folder if you want to automatically use this layout after every login.
