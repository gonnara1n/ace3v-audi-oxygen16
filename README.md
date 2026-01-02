# Oxygen OS 16 for OnePlus Ace 3v
Porting Oxygen OS from OnePlus Nord 4 to OnePlus Ace 3v
Device codename : audi
Android Version : 16

# Bugs (all are not critical) :
- opening camera by double-clicking power button disappears after reboot
- play integrity check fail (google **pay (not play)** not working without root interference)
- brightness curve is a little off—the brightness isn't adjusted evenly, but I don't see this as a problem; when the brightness is lowered all the way, the screen **doesn't go black**

# Install steps :
0.1. Install adb/fastboot drivers
0.2. Unlock the bootloader
0.3. Unzip the firmware archive
1.1. Put the phone into fastboot mode and connect it to the PC.
1.2. Run PJF110EN.bat and you will see recomendations to install (i recommend to *clean install*
2.1. Press any key
2.2. Press any key
2.3. When a numbered list appears, enter 2 and press Enter
2.4. Then enter Y and press Enter
2.5. The firmware will begin flashing. During the process, the phone will reboot into fastboot mode twice. Leave it alone and wait for the installation to complete.
3. After installation, the phone will boot into the system and you will see the welcome screen (at this point, you can disconnect the phone from the PC).
4. Go to developer settings and enable "Disable permission control."
