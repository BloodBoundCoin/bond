
Debian
====================
This directory contains files used to package BLOOD_BOUND_MASTERNODEd/BLOOD_BOUND_MASTERNODE-qt
for Debian-based Linux systems. If you compile BLOOD_BOUND_MASTERNODEd/BLOOD_BOUND_MASTERNODE-qt yourself, there are some useful files here.

## BLOOD_BOUND_MASTERNODE: URI support ##


BLOOD_BOUND_MASTERNODE-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install BLOOD_BOUND_MASTERNODE-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your BLOOD_BOUND_MASTERNODEqt binary to `/usr/bin`
and the `../../share/pixmaps/BLOOD_BOUND_MASTERNODE128.png` to `/usr/share/pixmaps`

BLOOD_BOUND_MASTERNODE-qt.protocol (KDE)

