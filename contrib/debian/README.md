
Debian
====================
This directory contains files used to package kumd/kum-qt
for Debian-based Linux systems. If you compile kumd/kum-qt yourself, there are some useful files here.

## kum: URI support ##


kum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kumqt binary to `/usr/bin`
and the `../../share/pixmaps/kum128.png` to `/usr/share/pixmaps`

kum-qt.protocol (KDE)

