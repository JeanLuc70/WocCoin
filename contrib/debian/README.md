
Debian
====================
This directory contains files used to package wocd/woc-qt
for Debian-based Linux systems. If you compile wocd/woc-qt yourself, there are some useful files here.

## woc: URI support ##


woc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install woc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your woc-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

woc-qt.protocol (KDE)

