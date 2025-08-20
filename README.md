# multiOS-cloner
#  multiOS-cloner

A lightweight toolkit to clone and boot multiple operating systems using GRUB. Ideal for forensic labs, recovery setups, and multi-boot experimentation.

##  Features
- Clone Linux-based OS partitions with minimal effort
- Auto-generate GRUB entries for cloned systems
- Supports ext4, Btrfs, and LVM setups
- Compatible with BIOS and UEFI boot modes
- Designed for ethical hacking labs and recovery workflows

## Usage
```bash
sudo ./multiOS-cloner.sh /dev/sdX /dev/sdY
