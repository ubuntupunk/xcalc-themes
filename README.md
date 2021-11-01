# xcalc-themes
I needed a decent calculator emulator :rainbow: on the command-line, to invoke via i3wm. I haven't found anything so far. But I guess [xcalc](https://github.com/thentenaar/xcalc) will have to do for now. 

Here is a collection of some themes for the x.org calculator, still very crude!

All questions regarding xcalc should be directed at the [Xorg mailing list](https://lists.x.org/mailman/listinfo/xorg)

The [xcalc code repository](
https://gitlab.freedesktop.org/xorg/app/xcalc) can be found at freedesktop.org


![default-color-image](/default-color.png) <img src="https://github.com/ubuntupunk/xcalc-themes/blob/main/forest.png"  width="250" height="380"></a>

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
