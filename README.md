# winbox-installer
A simple helper script to install winbox in GNU/Linux

## Feature:
1. Supported GNU/Linux distributtions: Debian, Ubuntu, Elementary OS, Linux Mint, Kali Linux, Fedora, RHEL, CentOS, IGOS Nusantara
2. Installs wine
3. Upgrade wine (from the distribution's repo) to a newer version (only for Fedora, RHEL, CentOS, IGN)
4. Menu entry in the application launcher
5. Latest winbox from https://mikrotik.com/download

## How to install:
Copy and paste this commands to your terminal
1. `wget -c https://github.com/mriza/winbox-installer/archive/v0.3.tar.gz`
2. `tar xvzf v0.3.tar.gz`
3. `cd winbox-installer-0.3`
4. `sudo bash setup install`

## Icon cache in GTK based desktop
Optional step for GTK based desktop, if the icon is not loaded or loaded with wrong size. Update icon cache with this command: `gtk-update-icon-cache -f -t /usr/share/icons/hicolor`

## How to Remove
If you want to remove winbox, just run this command: `sudo bash ./winbox-installer-master/setup remove`
