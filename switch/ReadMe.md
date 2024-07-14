Turn off device, remove Micro-SD, add to card reader in PC  
Update Hekate: https://github.com/CTCaer/hekate/releases  
(Rename hekate...-.bin to payload.bin, copy into bootloader directory )
Update Atmosphere: https://github.com/Atmosphere-NX/Atmosphere/releases
Add signature patches to hekate and atmosphere https://wiidatabase.de/switch-downloads/hacks/signatur-patches/  
Download Firmware: https://darthsternie.net/switch-firmwares/ or https://archive.org/download/nintendo-switch-global-firmwares  
Extract firmware.zip and put .nca files on Micro-SD card  
Start Hekate -> tools -> fix archive bit (Archive bit might be set on folders, this leads to corrupte Atmosphere boot)  
Boot to CFWsysnand  
Run Daybreak (Album, Install -> Select folder, select preserve settings, select fat32+Exfat)  
see: https://psxtools.de/forum/index.php?thread/82327-daybreak-ein-open-source-firmware-updater-downgrader-f%C3%BCr-ams/
