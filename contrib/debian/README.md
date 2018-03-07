
Debian
====================
This directory contains files used to package bitcoinneutrald/bitcoinneutral-qt
for Debian-based Linux systems. If you compile bitcoinneutrald/bitcoinneutral-qt yourself, there are some useful files here.

## bitcoinneutral: URI support ##


bitcoinneutral-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoinneutral-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoinneutralqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoinneutral128.png` to `/usr/share/pixmaps`

bitcoinneutral-qt.protocol (KDE)

