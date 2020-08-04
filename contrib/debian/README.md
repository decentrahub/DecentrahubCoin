
Debian
====================
This directory contains files used to package decentrahubd/decentrahub-qt
for Debian-based Linux systems. If you compile decentrahubd/decentrahub-qt yourself, there are some useful files here.

## decentrahub: URI support ##


decentrahub-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install decentrahub-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your decentrahub-qt binary to `/usr/bin`
and the `../../share/pixmaps/decentrahub128.png` to `/usr/share/pixmaps`

decentrahub-qt.protocol (KDE)

