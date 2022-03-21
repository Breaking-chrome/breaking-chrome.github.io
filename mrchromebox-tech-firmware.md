## MrChromebox's custom firmware
WARNING: Always check that it can be done on your device, *especiallly* with custom firmware. It could brick your device. Info on that [here](https://mrchromebox.tech/#devices).

Most ways to get Ubuntu/Another OS on Chromebook require custom coreboot firmware to access and update the laptop's BIOS (The SeaBIOS) and to be able to run another operating system or remove ChromeOS and download another OS. The commands you need to do to update the BIOS is `cd; curl -LO mrchromebox.tech/firmware-util.sh`, `sudo install -Dt /usr/local/bin -m 755 firmware-util.sh` and `sudo firmware-util.sh` (in that order). Type `1` and press enter, type `y` and enter, then once it has finished installing press enter. Do the same process again but this time type `2` where `1` should be. 

Other MrChromebox options are UEFI, Boot options, HWID, Bitmap removers, Restore stock BOOT_STUB, Restore stock Firmware and the Ubuntu installer. These will be listed [here](kodiubuntu.md).

[Home](index.md)
