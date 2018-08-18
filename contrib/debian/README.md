
Debian
====================
This directory contains files used to package reeved/reeve-qt
for Debian-based Linux systems. If you compile reeved/reeve-qt yourself, there are some useful files here.

## reeve: URI support ##


reeve-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install reeve-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your reeveqt binary to `/usr/bin`
and the `../../share/pixmaps/reeve128.png` to `/usr/share/pixmaps`

reeve-qt.protocol (KDE)

