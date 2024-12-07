# Pictochat Remote Installer

**Get PictoChat on every DS device—even if it didn’t originally come with it!**

This repository provides a solution for bringing PictoChat to any Nintendo DS, DS Lite, DSi, 2DS, or 3DS system using a modded version of the DS Download Station broadcaster.

---

## How It Works

The core of this project is the `pictochat_remote_install.nds` file, which:
- Uses **Haxxstation** as a base to broadcast a customized DS Download Play channel.
- Distributes a ROM of **PictoChat**, extracted from a DSi firmware dump and transplanted into a standalone ROM.
- Allows PictoChat to be downloaded via **DS Download Play** to compatible devices.

This process makes it possible to run PictoChat on DS and 3DS family systems, even those that didn’t originally include the application.

---

## Features

- **Universal Compatibility**:  
  Broadcasts PictoChat to any DS, DS Lite, DSi, 3DS, 2DS, or other Nintendo devices with Download Play support.

- **Multiple Setup Options**:  
  - Use a hacked 3DS, DSi, or DS with a flashcart to run the installer.
  - Alternatively, emulate the `.nds` file on a PC with Bluetooth adapters to broadcast wirelessly.

- **Open-Source and Customizable**:  
  This project is based on **Haxxstation** and uses modified code from the DS Download Station to enable seamless broadcasting.

---

## Requirements

1. A device capable of running homebrew or custom firmware, such as:
   - Hacked 3DS or 2DS
   - Modded DSi
   - DS/DS Lite with a flashcart
   - PC emulator with Bluetooth capabilities

2. The file `pictochat_remote_install.nds` (included in this repository).

3. A target device with **Download Play** support to receive PictoChat.

---

## Installation

1. **Download the Installer**:
   - Clone this repository or download the file `pictochat_remote_install.nds`.

2. **Load the Installer**:
   - On a hacked 3DS or DSi: Copy the `.nds` file to your SD card and run it using your preferred homebrew loader.
   - On a DS or DS Lite: Copy the file to your flashcart.
   - On a PC: Use an emulator capable of running `.nds` files and set up Bluetooth broadcasting.

3. **Run the Installer**:
   - Start the `pictochat_remote_install.nds` on your broadcasting device.
   - This will open a DS Download Play channel, making the PictoChat ROM available for download.

4. **Receive PictoChat**:
   - On the target device, open **DS Download Play**.
   - Select the PictoChat broadcast and follow the prompts to install and launch it.

---

## Notes

- This project is for educational purposes and personal use only.
- Ensure you are compliant with copyright laws in your region. The PictoChat ROM was extracted from a firmware dump of a DSi and is redistributed here for non-commercial purposes.

---

## Acknowledgments

- Based on **Haxxstation**, the modded DS Download Station broadcaster for homebrew and exploit distribution.
- Inspired by the goal of making PictoChat accessible on all Nintendo DS devices.

---

### Disclaimer

This software is provided as-is without warranty of any kind. Use at your own risk. The author is not responsible for any damages or violations resulting from the use of this tool.
