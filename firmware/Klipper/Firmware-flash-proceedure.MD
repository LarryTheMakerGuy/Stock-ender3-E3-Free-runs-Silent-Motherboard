1. Format SD card to Fat 32 (sudo mkfs.fat -s 8 /dev/sdX1).
2. Create STM32F4_UPDATE folder at root.
3. Copy Klipper_CR4NTxxC10.bin in the new directory.
4. Remove the jumper that may be between MS and 3.3v.
5. Insert SD card, turn on the printer, and let it flash for 60 seconds.
6. Check for the USB device on the print server.
7. Update printer.cfg [mcu] section with appropriate usb  'path by ID'
