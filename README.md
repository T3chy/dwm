# Elam(Actually mostly Luke Smith)'s build of dwm

## What's special about my fork?
- use modkey + J and modkey + K to switch focus from one monitor to anotehr
- use modkey + L and modkey + H to send the selected window to the other monitor!
- ctrl-g uses dmenu and surf to google whatever u type in (defaults to clipboard if you don't enter anything)
- ctrl-n uses dmenu to select a playlist (look at my .scripts repo)
- it's suckless baby! Just read the config.h for all the bindings :)
kinda vim like ish lol

## Please install `libxft-bgra`!

This build of dwm does not block color emoji in the status/info bar, so you must install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR, which fixes a libxft color emoji rendering problem, otherwise dwm will crash upon trying to render one. Hopefully this fix will be in all libxft soon enough.
