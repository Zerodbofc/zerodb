
Debian
====================
This directory contains files used to package zerodbd/zerodb-qt
for Debian-based Linux systems. If you compile zerodbd/zerodb-qt yourself, there are some useful files here.

## zerodb: URI support ##


zerodb-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zerodb-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zerodbqt binary to `/usr/bin`
and the `../../share/pixmaps/zerodb128.png` to `/usr/share/pixmaps`

zerodb-qt.protocol (KDE)

