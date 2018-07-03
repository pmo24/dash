
Debian
====================
This directory contains files used to package flashd/flash-qt
for Debian-based Linux systems. If you compile flashd/flash-qt yourself, there are some useful files here.

## flash: URI support ##


flash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install flash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your flash-qt binary to `/usr/bin`
and the `../../share/pixmaps/flash128.png` to `/usr/share/pixmaps`

flash-qt.protocol (KDE)

