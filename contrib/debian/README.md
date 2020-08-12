
Debian
====================
This directory contains files used to package bitcoinnexxd/bitcoinnexx-qt
for Debian-based Linux systems. If you compile bitcoinnexxd/bitcoinnexx-qt yourself, there are some useful files here.

## bitcoinnexx: URI support ##


bitcoinnexx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoinnexx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoinnexxqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoinnexx128.png` to `/usr/share/pixmaps`

bitcoinnexx-qt.protocol (KDE)

