### Ender-3 V3 Firmware Update Guide:
- 1.0.6 - Oct 25, 2023
- 1.0.4 - Aug 14, 2023
- Printer: Ender-3 V3 SE
- Printer Mainboard: HWCR4NS200320C13

#### General Notes:
*The firmware is Ender-3V3 SE Factory standard version，Support ten languages*

**Display firmware update:**
1. Format the SD card on the computer side, and select `4096` for the allocation unit size.
2. Put the file "`TJC_SET`" into the SD card.
3. Turn off the printer and Insert the TF card into the card slot on the left side of the screen.
4. Reboot and wait for the update to finish.
5. After finishing the update, remove the TF card and delete the files inside.

**Mainboard firmware update:**
1. Format the TF card on the computer side, and select `4096` for the allocation unit size.
2. Put the firmware file "`Ender-3 V3 SE_HWCR4NS200320C13_SWV<VERSION>._GD303_<DATE>.bin`" into the root directory of SD card.
3. Turn off the printer and insert the TF card into the card slot on the motherboard.
4. Reboot and wait for the update to finish.
5. After finishing the update, remove the TF card from the motherboard slot and delete the bin file inside.