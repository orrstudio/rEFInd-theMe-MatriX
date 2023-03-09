# rEFInd-theMe-MatriX
A rEFInd theme based on the scene from the movie Matrix where Morpheus offers the two pills to Neo.


![](screenshot.png)

A clean theme for the [rEFInd UEFI Boot Manager](http://www.rodsbooks.com/refind/)
based on the default colorscheme.

On the default theme we roll our icons, fonts and add background picture.

## Installation

1. Find the boot directory on your boot volume. For me, it's "/boot". And delete all files in to boot directory. (Do so with care at your own risk. If you don't know what you're doing, it's best not to.)

2. Copy all files from "boot" folder to the same directory inside the boot directory.

3. I configured two systems in my refind.conf file: Arch Linux and Windows 10 (If you want, you can change it to your liking.)

4. Ready! Enjoy...

## Description of the list of files in the "/boot" directory:

 - "EFI" - folder for bios Boot folder and rEFInd configuration files.
 - "BCD" - Windows 10 loader
 - "bootmgfw.efi" - Windows 10 boot loader
 - "initramfs-linux.img" - Linux RAM disk (a temporary root file system to mount its real root file system.)
 - "initramfs-linux-fallback.img" - Linux RAM disk fallback
 - "vmlinuz-linux" - Linux kernel
 - "/boot/EFI/Boot/bootx64.efi" - Renamed from rEFInd.efi
 - "/boot/EFI/Boot/refind.conf" - rEFInd config file
 - "/boot/EFI/Boot/icons/" - folder for icons, background pict, fonts and other.

## Additional Info

Additional information about configuring rEFInd may be found [here](http://www.rodsbooks.com/refind/configfile.html).
