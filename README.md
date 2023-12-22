# Arch/Linux useful tools and tricks
A collection of links to tools and tricks for Arch (Linux)


## Need to have's
[Snapper](https://wiki.archlinux.org/title/snapper) ([Btrfs](https://wiki.archlinux.org/title/Btrfs) only) Snapper stores snapshots of your system so if anything goes wrong you can easliy restore to the last snapshot. I personally use the AUR version [snapper-support](https://aur.archlinux.org/packages/snapper-support) which supports GRUB boot options. snapper-support installs snapper and pacman hooks to automatically create snapshots on update, install or removed packages.
Alternavity [snap-pac-grub](https://aur.archlinux.org/packages/snap-pac-grub) should provide the feature to snapper.

[Linux-zen](https://archlinux.org/packages/extra/x86_64/linux-zen/) is a great improvement over the default kernel and is officially support by ARCH

## Pipewire
[Pipewire Performance tuning](https://gitlab.freedesktop.org/pipewire/pipewire/-/wikis/Performance-tuning) prevents the audio stooping or clipping on high CPU or other events where Pipewire might get intrupted.


## Laptop / Power Management
[Tuxedo Control Center](https://github.com/tuxedocomputers/tuxedo-control-center) is a control center which allows the user to configure CPU cores, Fans Profile and more (Tuxedo sort of supports all Intel Tongfang laptops from brands like Eluktronics, PCSpecialist, Laptopparts4less, NextCore and many more)

[KDE Plasma Intel CPU Management Widget](https://github.com/frankenfruity/plasma-pstate) is a great widget for managing power, temperature. Allowing the control over the TCC (Thermal Control Curcit) which is the greatest feature allows controlling the tempature your Intel CPU throttles at.

## Monitoring
[BTOP](https://github.com/aristocratos/btop) is a great terminal interface for monitoring CPU, Memory, Disks, Network, Battery, Procceses And Tempature. A grealy improvement over the original TOP command

## KDE
[Tilting Manager for KDE Bismuth](https://github.com/Bismuth-Forge/bismuth) Tilting manager for KDE
