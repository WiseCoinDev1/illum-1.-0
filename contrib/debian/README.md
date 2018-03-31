
Debian
====================
This directory contains files used to package illuminumd/illuminum-qt
for Debian-based Linux systems. If you compile illuminumd/illuminum-qt yourself, there are some useful files here.

## illuminum: URI support ##


illuminum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install illuminum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your illuminum-qt binary to `/usr/bin`
and the `../../share/pixmaps/illuminum128.png` to `/usr/share/pixmaps`

illuminum-qt.protocol (KDE)

