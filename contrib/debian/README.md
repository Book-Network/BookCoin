
Debian
====================
This directory contains files used to package bookd/book-qt
for Debian-based Linux systems. If you compile bookd/book-qt yourself, there are some useful files here.

## book: URI support ##


book-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install book-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your book-qt binary to `/usr/bin`
and the `../../share/pixmaps/book128.png` to `/usr/share/pixmaps`

book-qt.protocol (KDE)

