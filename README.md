# xcalc-themes
I needed a decent calculator emulator on the command-line, to invoke via i3wm. I haven't found anything so far. But I guess xcalc will have to do for now. 

Here are some themes for the x.org calculator, still very crude!

# Installation
1. place themes in .xres or anywhere else you wish.

2. call them by placing something like this inside your .Xresources

```
! SOURCE PROGRAM SPECIFIC FILES !
#include "/home/<user>/.xres/xcalc/theme1"
```

3. Remember to invoke xrdb

```
xrdb .Xresources
```
