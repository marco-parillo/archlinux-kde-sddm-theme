Archlinux Theme for SDDM
------------------------
SDDM is a Login Manager for Linux which can be themed by qml. This is a port of existing kdm themes (package archlinux-themes-kdm) to SDDM.

Hat-tip to the theme available through [AUR](https://aur.archlinux.org/packages/archlinux-themes-sddm/)

![archlinux-kde](https://github.com/marco-parillo/archlinux-kde-sddm-theme/raw/master/archlinux-kde/screenshot.png "archlinux-kde")

Manual Installation
-------------------
* Copy the folder to /usr/share/sddm/themes/
```
$ sudo cp -r archlinux-kde-sddm-theme/  /usr/share/sddm/themes/

```
* Then, either change the current theme in System Settings; or: 
```
$ sudo vim /etc/sddm.conf
[Theme]
Current=archlinux-kde 
```

* Have fun!
