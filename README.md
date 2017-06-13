# zaurus_cxx00

 pdaXii13 for Zaurus SL-C3000

These files are for installing pdaXii13. Use at your own risk. Ensure you know how to restore a working distro before attempting to flash this in case it does not work out for you or you want to revert back to your previous distro.


The first stable pdaXii13 Spitz (Alice) release is build5.2 - see notes on build5.3.x for new features and updates.

build 5.3.x is an update of build 5.2 and upgrading can be achieved in two ways. The first method is to just flash build 5.3.x. This method is clean but you lose all your custom installed applications and settings. You do not need to repartition your MicroDrive for this and you can choose not to reformat hdd3 so you won't lose anything that is stored there, but hdd1 will get reformatted. The second method is to install the packages mentioned on the notes for build 5.3.x from the custom feed. This way, you won't loose any settings but it requires a bit more work.

updater/flash utility

updater.sh (18KB) - v0.26
updater-tools.bin (1.2MB) - build 15


kernel and updated bootloader
initrd.bin (2.5MB) - v0.5a
zImage-2.4.20.bin (1.1MB) - 2.4.20


distro images for the microdrive
You need one of these hd images.
hdimage-base.tgz (42MB) - build 5.4.9
hdimage-full.tgz (200MB) - build 5.4.9
