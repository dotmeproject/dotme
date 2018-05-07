
Debian
====================
This directory contains files used to package dotmed/dotme-qt
for Debian-based Linux systems. If you compile dotmed/dotme-qt yourself, there are some useful files here.

## dotme: URI support ##


dotme-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dotme-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dotmeqt binary to `/usr/bin`
and the `../../share/pixmaps/dotme128.png` to `/usr/share/pixmaps`

dotme-qt.protocol (KDE)

