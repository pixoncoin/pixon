
Debian
====================
This directory contains files used to package pixond/pixon-qt
for Debian-based Linux systems. If you compile pixond/pixon-qt yourself, there are some useful files here.

## pixon: URI support ##


pixon-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pixon-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pixon-qt binary to `/usr/bin`
and the `../../share/pixmaps/pixon128.png` to `/usr/share/pixmaps`

pixon-qt.protocol (KDE)

