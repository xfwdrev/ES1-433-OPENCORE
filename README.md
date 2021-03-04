# Acer Aspire ES1-433


## Specifications

- Processor: Dual Core 2.00 GHz Intel Core i3-6006U
- Memory: 8GB SK Hynix DDR4 2133 MHz Dual Channel
- Integrated GPU: Intel HD Graphics 520
- Audio: Realtek ALC255
- Storage: Morebeck N100 256GB M.2 SSD , TOSHIBA MK5065GSXF 500GB HDD
- Ethernet Card: Realtek RTL8168
- Wireless Card: Intel Dual Band Wireless AC 7265
- Touchpad: ELAN0501 I2C
- Keyboard: PS2 Keyboard
- Resolution: 1366x768
- Bootloader: OpenCore 0.6.6 RELEASE
- OS Version: macOS 11.2.1 Big Sur
- SMBIOS: MacBookPro15,4

## What's Working?

- Power Management, idle @500-800MHz
- Power Option
- QE/CI for Intel HD Graphics 520
- WiFi (Had to replace the stock QCA9377 as it is not supported)
- Brightness (Brightness Keys also using Arrow Keys)
- Battery Management
- Ethernet (Realtek RTL8XXX)
- Trackpad Full Gestures (VoodooPS2Trackpad) - GPIO Buggy always return pin 0x0 so I2C Not Possible. Change to Basic Trackpad Function in BIOS
- Keyboard
- USB 3.0 + USB 2.0 Ports
- HDMI (Audio and Video Out)
- Speaker + Combo Jack Headphone
- Native NVRAM

## Not Working

- Microphone from Combo Jack Interface
- SD Card reader (Using USB Interface so it is not supported)
- Facetime and iMessage (Automatically Logging out of the application)
- DRM is broken (iGPU only not supported)

## Credit

- Acidanthera
- Alexandred, VoodooPS2
- OpenIntelWireless
- RehabMan
- Andres
