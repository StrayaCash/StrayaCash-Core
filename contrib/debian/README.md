
Debian
====================
This directory contains files used to package strayacashd/strayacash-qt
for Debian-based Linux systems. If you compile strayacashd/strayacash-qt yourself, there are some useful files here.

## strayacash: URI support ##


strayacash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install strayacash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your strayacashqt binary to `/usr/bin`
and the `../../share/pixmaps/strayacash128.png` to `/usr/share/pixmaps`

strayacash-qt.protocol (KDE)

