# Redragon Draconic xkb remap

## Redragon Draconic xkb remap with spanish and portuguese keys (Ubuntu 20.04 with Xorg display manager)

![Keyboard Layout](keyboard_layout.png)

```bash
$ sudo cp /usr/share/X11/xkb/rules/evdev.xml /usr/share/X11/xkb/rules/evdev.xml.bak
$ sudo cp /usr/share/X11/xkb/rules/evdev.lst /usr/share/X11/xkb/rules/evdev.lst.bak
```

```bash
$ sudo cp drac /usr/share/X11/xkb/symbols
$ sudo cp evdev.xml.custom /usr/share/X11/xkb/rules/evdev.xml
$ sudo cp evdev.lst.custom /usr/share/X11/xkb/rules/evdev.lst
```

- Logout and login
- Select keyboard
