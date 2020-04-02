# fApple-A1243-keyboard-layout
Windows layout/driver for A1243 Apple Keyboard - remapped cmd/Alt keys for proper Windows functions

To make your own mod download and install M$ Keyboard Layout Creator.
Go to c:\Program Files (x86)\Microsoft Keyboard Layout Creator 1.4\inc\ and use my patch file on kdb.h:

patch --binary kbd.h fApple-mod-keys.patch

This will give you base functionality of Windows standard mod keys on A1243 keyboard:

> LAlt => WinKey
> LCmd => LAlt
> RCmd => AltGr/RAlt
> RAlt => AppsMenu
