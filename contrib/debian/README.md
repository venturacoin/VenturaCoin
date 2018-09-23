
Debian
====================
This directory contains files used to package venturad/ventura-qt
for Debian-based Linux systems. If you compile venturad/ventura-qt yourself, there are some useful files here.

## ventura: URI support ##


ventura-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ventura-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your venturaqt binary to `/usr/bin`
and the `../../share/pixmaps/ventura128.png` to `/usr/share/pixmaps`

ventura-qt.protocol (KDE)

