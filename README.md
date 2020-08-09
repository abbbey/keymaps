
# Keymaps

qmk keymap used for Iris split keyboard

**To modify:**

Use QMK configurator online and upload \*.json keymap.

https://config.qmk.fm

**To flash:**
1. Reset dominant board half
1. Check that atmega32u4 dfu bootloader comes up in lsusb
1. `sudo dfu-programmer atmega32u4 erase --force`
1. `sudo dfu-programmer atmega32u4 flash keebio_iris_rev4_purps.hex`
1. `sudo dfu-programmer atmega32u4 reset`
