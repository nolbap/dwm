#nolbap's dwm build

My fully functional and patched dwm build.

Patches:
- Gaps
- Actual fullscreen
- Swallow
- Resize corners
- Shiftview
- Dragmfact
- Mpd
- Monocle and Centeredmaster layout

Dependencies:

These are the programms I use for the bindings I have configured:
- xbacklight
- amixer
- Sí-no script (see my dotfiles)
- htop
- ytop
- calcurse
- ncmpcpp
- lf (you could change this file manager to ranger for example but ranger doesn't work with the swallow patch)
- scrot
- doas
- ~gentoo~

Bindings:

- Default dwm bindings
- Super+d	dmenu
- Super+enter	terminal
- Super+q	kill
- Super+t	tiling layout
- Super+c	centered master layout
- Super+space	toggle floating on selected window
- Super+f	toggle fullscreen on selected window
- Super+F1	previous mpd song
- Super+F2	next mpd song
- Super+ESC	pause mpd
- Upvolkey	vol +2%
- Downvolkey	vol -2%
- Mutevolkey	toggle mute
- Super+plus	xbacklight +2%
- Super+minus	xbacklight -2%
- Super+Shift+c reboot prompt
- Super+Shift+x	shutdown prompt
- Super+m 	htop
- Super+Shift+m ytop
- Super+Shift+i	calcurse
- Super+Shift+n ncmpcpp
- Super+r	lf
- Super+Shift+r root lf
- Print		screenshot
- Shift+Print	prompt select area screenshot

Further Configuration:

I've set a few static values that you could change as well.

Font: Change "*fonts" string on config.h.
Color: Change "col_cyan" string on config.h to match your rice.
Bar height: Change "bh = 19" string on dwm.c.
