# Installation

Run this in your install

git clone https://github.com/SkywareSW/SkywareOS-Testing \
cd SkywareOS-Testing\
chmod +x skyware-testingsetup.sh\
./skyware-testingsetup.sh

# Documentation

* Ware

* ware status - Shows kernel and version, Uptime, Available updates, Firewall status, Disk usage, Memory usage, Current desktop and current channel

* ware install - Searches for said package through pacman, flatpak and aur and then proceeds to install it

* ware remove - Removes package from system

* ware update - Updates system and or specific package

* ware upgrade - Installs and runs the latest version of SkywareOS Testing

* ware switch - Switches from the Testing channel to the Release channel

* ware power (balanced/performance/battery) - Switches power mode to either of those three depending on the selection

* ware dm list - Lists available display managers

* ware dm status - Shows currently active display manager

* ware dm switch(sddm/gdm/lightdm) - Switch between the available display managers

* ware search - Searches for the package or closest matching keyword in pacman, flatpak and aur

* ware info - Gives available information on a package

* ware list - Shows installed packages

* ware doctor - Searches for and fixes any corrupt or broken packages/dependencies, then checks the firewall status

* ware clean - Removes unused repositories/packages

* ware autoremove - Automatically removes unused packages

* ware sync - Syncs mirrors

* ware interactive - Simpler way to install a package

* ware --json - Run a custom command/script using JSON

* ware setup hyprland - Automatically Sets up hyprland with jakoolit's dotfiles

* ware setup lazyvim - Automatically sets up Lazyvim

* ware setup niri - Automatically sets up Niri (EXPERIMENTAL)

* ware setup mango - Automatically sets up MangoWC (EXPERIMENTAL)

* ware setup dwm - Automatically sets up DWM (EXPERIMENTAL)
