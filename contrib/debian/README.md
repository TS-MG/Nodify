
Debian
====================
This directory contains files used to package nodifyd/nodify-qt
for Debian-based Linux systems. If you compile nodifyd/nodify-qt yourself, there are some useful files here.

## nodify: URI support ##


nodify-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nodify-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nodifyqt binary to `/usr/bin`
and the `../../share/pixmaps/nodify128.png` to `/usr/share/pixmaps`

nodify-qt.protocol (KDE)

