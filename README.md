# winbox-installer
A simple helper script to install winbox in GNU/Linux

## Feature:
1. Supported GNU/Linux distributtions: Debian, Ubuntu, Elementary OS, Zorin OS, Linux Mint, Kali Linux, Fedora, RHEL, CentOS, IGOS Nusantara
2. Installs wine
3. Upgrade wine (from the distribution's repo) to a newer version (only for Fedora, RHEL, CentOS, IGN)
4. Menu entry in the application launcher
5. Latest winbox from https://mikrotik.com/download

## How to install:
Copy and paste this commands to your terminal
1. `cd /tmp`
2. `git clone https://github.com/mriza/winbox-installer.git`
3. `cd winbox-installer`
4. `sudo ./winbox-setup install` OR `sudo sh winbox-setup install`

## Icon cache in GTK based desktop
Optional step for GTK based desktop, if the icon is not loaded or loaded with wrong size. Update icon cache with this command: `gtk-update-icon-cache -f -t /usr/share/icons/hicolor`

## How to Remove
If you want to remove winbox, just run this command: `sudo ./winbox-setup remove` OR `sudo ./winbox-setup remove`
