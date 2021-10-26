
Debian
====================
This directory contains files used to package ajwmd/ajwm-qt
for Debian-based Linux systems. If you compile ajwmd/ajwm-qt yourself, there are some useful files here.

## ajwm: URI support ##


ajwm-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ajwm-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ajwm-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

ajwm-qt.protocol (KDE)

