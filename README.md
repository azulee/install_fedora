# install_fedora
=================================

1. You should check your bios if "secure boot" is enabled; if so, turn it off.
2. Remove bcmwl-kernel-source
`sudo apt-get purge bcmwl-kernel-source`
3. Re-install bcmwl-kernel-source
`sudo apt-get update && sudo apt-get install bcmwl-kernel-source`
4. Reboot. Your wireless should now be working.