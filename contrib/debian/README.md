
Debian
====================
This directory contains files used to package ONEMd/ONEM-qt
for Debian-based Linux systems. If you compile ONEMd/ONEM-qt yourself, there are some useful files here.

## ONEM: URI support ##


ONEM-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ONEM-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ONEM-qt binary to `/usr/bin`
and the `../../share/pixmaps/ONEM128.png` to `/usr/share/pixmaps`

ONEM-qt.protocol (KDE)

