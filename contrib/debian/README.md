
Debian
====================
This directory contains files used to package cabyxd/cabyx-qt
for Debian-based Linux systems. If you compile cabyxd/cabyx-qt yourself, there are some useful files here.

## cabyx: URI support ##


cabyx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cabyx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cabyxqt binary to `/usr/bin`
and the `../../share/pixmaps/cabyx128.png` to `/usr/share/pixmaps`

cabyx-qt.protocol (KDE)

