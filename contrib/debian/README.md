
Debian
====================
This directory contains files used to package lkcoind/lkcoin-qt
for Debian-based Linux systems. If you compile lkcoind/lkcoin-qt yourself, there are some useful files here.

## lkcoin: URI support ##


lkcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lkcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lkcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/lkcoin128.png` to `/usr/share/pixmaps`

lkcoin-qt.protocol (KDE)

