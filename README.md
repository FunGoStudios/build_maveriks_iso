build_maveriks_iso
==================

To download a source image, go to the app store and choose dowload Marverick or Lion (not install)
http://support.apple.com/kb/HT5855  

./build_maveriks_iso.sh /Applications/Install\ OS\ X\ Mavericks.app/Contents/SharedSupport/InstallESD.dmg /tmp/

You need at least 16 GB
Mount install.cdr as cdrom in your VirtualBox and boot
The boot is slow and prints some errors but it works!

NB: when you first boot there are no disks available for install, you need to create a partion from the menu -> Disk Utility

ref: http://www.insanelymac.com/forum/topic/293481-how-to-create-a-bootable-iso-from-the-mavericks-installesddmg/
