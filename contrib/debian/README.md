
Debian
====================
This directory contains files used to package PRACTICE1d/PRACTICE1-qt
for Debian-based Linux systems. If you compile PRACTICE1d/PRACTICE1-qt yourself, there are some useful files here.

## PRACTICE1: URI support ##


PRACTICE1-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install PRACTICE1-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your PRACTICE1qt binary to `/usr/bin`
and the `../../share/pixmaps/PRACTICE1128.png` to `/usr/share/pixmaps`

PRACTICE1-qt.protocol (KDE)

