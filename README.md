# CFP's build of dwm

Another fork of dwm. It is less patched (specifically concerning the status monitor) and has different keybinds as it's intended to work with the IBM Model M I have in my office (`MODKEY` is set to the `ALT`key, not the `SUPER` key). For documentation, refer to [the original website](https://dwm.suckless.org/).

## Applied patches:
- [accessnthmonitor](https://dwm.suckless.org/patches/accessnthmonitor/)
- [adjacenttag](https://dwm.suckless.org/patches/adjacenttag/)
- [alwayscenter](https://dwm.suckless.org/patches/alwayscenter/)
- [attachbottom](https://dwm.suckless.org/patches/attachbottom/)
- [barpadding](https://dwm.suckless.org/patches/barpadding/)
- [bartabgroups](https://dwm.suckless.org/patches/bartabgroups/)
- [focusonnetactive](https://dwm.suckless.org/patches/focusonnetactive/)
- [fullscreen](https://dwm.suckless.org/patches/fullscreen/)
- [hide vacant tags](https://dwm.suckless.org/patches/hide_vacant_tags/)
- [movestack](https://dwm.suckless.org/patches/movestack/)
- [pertag](https://dwm.suckless.org/patches/pertag/)
- [preserveonrestart](https://dwm.suckless.org/patches/preserveonrestart/)
- [statusallmons](https://dwm.suckless.org/patches/statusallmons/)
- [statuspadding](https://dwm.suckless.org/patches/statuspadding/)
- [swallow](https://dwm.suckless.org/patches/swallow/)
- [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/)
- [warp](https://dwm.suckless.org/patches/warp/)

## Requirements:
Xlib header files. On Arch-based systems:

```bash
# pacman -S libx11
```

## Installation:
Edit config.mk and config.h and run:

```bash
# make clean install
```
