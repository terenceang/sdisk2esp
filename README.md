# SDISK2 ESP

## An Apple 2 floppy Emulator using ESP32

This is a project to update the original SDISK2 project by Koichi Nishida (2013).  
It uses it to read the Disk controller signals and return the track data from the disk image.
A basic UI will be used to select and load an image.

### Todo

1. UI
2. Decode Disk images
3. Disk II emulation.

### Parts

1. ESP32 dev kit 1
2. SSD1306 i2c OLED module.
3. SDcard Module
4. TP223 x 3
5. 74HCT125 (or other 3.3v to 5v translator)

Original SDISK II project.
<https://tulip-house.ddo.jp/digital/SDISK2/english.html>
