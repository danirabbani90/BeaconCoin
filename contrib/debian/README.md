
Debian
====================
This directory contains files used to package BeaconCoind/BeaconCoin-qt
for Debian-based Linux systems. If you compile BeaconCoind/BeaconCoin-qt yourself, there are some useful files here.

## BeaconCoin: URI support ##


BeaconCoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install BeaconCoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your BeaconCoinqt binary to `/usr/bin`
and the `../../share/pixmaps/BeaconCoin128.png` to `/usr/share/pixmaps`

BeaconCoin-qt.protocol (KDE)

