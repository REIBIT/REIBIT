
Debian
====================
This directory contains files used to package reibitd/reibit-qt
for Debian-based Linux systems. If you compile reibitd/reibit-qt yourself, there are some useful files here.

## reibit: URI support ##


reibit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install reibit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your reibit-qt binary to `/usr/bin`
and the `../../share/pixmaps/reibit128.png` to `/usr/share/pixmaps`

reibit-qt.protocol (KDE)

