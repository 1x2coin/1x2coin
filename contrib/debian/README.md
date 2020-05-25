
Debian
====================
This directory contains files used to package 1x2coind/1x2coin-qt
for Debian-based Linux systems. If you compile 1x2coind/1x2coin-qt yourself, there are some useful files here.

## 1X2coin: URI support ##


1x2coin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install 1x2coin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your 1x2coinqt binary to `/usr/bin`
and the `../../share/pixmaps/1x2coin128.png` to `/usr/share/pixmaps`

1x2coin-qt.protocol (KDE)

