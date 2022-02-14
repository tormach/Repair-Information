39146 Fuse Settings:
====================
Note: On some stock 39146 boards hfuse may be set to 0x99. If you are flashing the flash.hex file in this folder, you must set the fuse to 9b as shown here:

lfuse: 0x5E
hfuse: 0x9b
efuse: 0xF3

Setting fuses:
--------------
avrdude -c usbasp -p at90usb1286 -U lfuse:w:0x5E:m
avrdude -c usbasp -p at90usb1286 -U hfuse:w:0x9b:m
avrdude -c usbasp -p at90usb1286 -U efuse:w:0xF3:m

Uploading 39146 Firmware:
=========================
**Make sure you are really confident that you want to erase your HID board before executing these steps. It will be inoperable if you fail to upload the hex file afterwards.**
avrdude -c usbasp -p at90usb1286 -e
avrdude -c usbasp -p at90usb1286 -v -U flash:w:flash.hex:i