
Debian
====================
This directory contains files used to package bitcoincardd/bitcoincard-qt
for Debian-based Linux systems. If you compile bitcoincardd/bitcoincard-qt yourself, there are some useful files here.

## bitcoincard: URI support ##


bitcoincard-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoincard-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoincardqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoincard128.png` to `/usr/share/pixmaps`

bitcoincard-qt.protocol (KDE)

