
Debian
====================
This directory contains files used to package dachd/dach-qt
for Debian-based Linux systems. If you compile dachd/dach-qt yourself, there are some useful files here.

## dach: URI support ##


dach-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dach-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dachqt binary to `/usr/bin`
and the `../../share/pixmaps/dach128.png` to `/usr/share/pixmaps`

dach-qt.protocol (KDE)

