# UTMBSD
Prebuilt Collection of BSD VMs for UTM for ARM64 architecture.

The most common mistake when installing  in UTM is due to the 

ARM64 BSD systems usually lacks ISO(CD/DVD) boot support for the ARM platforms in general. When creating a new virtual machine with the Wizard, make sure to edit the machine first to change the device type of the USB boot device from CD/DVD to DISK.

All machines are installed with root root passwords. 
For your safety, please change this password immediatly at first boot.

## OpenBSD
OpenBSD 7.5 (ARM64), Default settings all packages. X11 is currently broken in ARM64.
https://github.com/sysaulab/UTMBSD/releases/tag/openbsd
