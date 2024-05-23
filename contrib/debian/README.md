
Debian
====================
This directory contains files used to package gymnasiumd/gymnasium-qt
for Debian-based Linux systems. If you compile gymnasiumd/gymnasium-qt yourself, there are some useful files here.

## gymnasium: URI support ##


gymnasium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gymnasium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gymnasium-qt binary to `/usr/bin`
and the `../../share/pixmaps/gymnasium128.png` to `/usr/share/pixmaps`

gymnasium-qt.protocol (KDE)

