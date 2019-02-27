
Debian
====================
This directory contains files used to package mtapd/mtap-qt
for Debian-based Linux systems. If you compile mtapd/mtap-qt yourself, there are some useful files here.

## mtap: URI support ##


mtap-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mtap-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mtapqt binary to `/usr/bin`
and the `../../share/pixmaps/mtap128.png` to `/usr/share/pixmaps`

mtap-qt.protocol (KDE)

