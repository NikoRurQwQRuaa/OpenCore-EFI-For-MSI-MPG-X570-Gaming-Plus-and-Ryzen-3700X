# OpenCore-EFI-For-MSI-MPG-X570-Gaming-Plus-and-Ryzen-3700X
-------
## illustrate

**This is a hacker boot, made qwq based on OpenCore**

**The current OpenCore version is 0.9.3 and supports macOS 14.0 Beta**

**macOS Catalina Bigsur Monterey Ventura has been tested before and can be booted, and the rest of the systems are self-tested**

----

## Overview
![overview](https://github.com/NikoRurQwQRuaa/OpenCore-EFI-For-MSI-MPG-X570-Gaming-Plus-and-Ryzen-3700X/blob/main/Photos.png)

---

**My computer configuration:**

**CPU:AMD Ryzen 3700X**

**Memory: 32GB DDR4 3200Mhz**

**Graphics card: AMD Radeon RX 570 8GB**

**Motherboard: MSI MPG X570 GAMING PLUS**

----
## Driver Support
---
Part|Model|Is it supported
:-|:-|:-|
CPU|AMD Ryzen 7 3700X|Support
Discrete Graphics | MSI AMD Radeon RX570 8GB | Support
NIC|RealtekRTL8111|Support
Hard disk | SanDisk SATA 128G SSD | support, Samsung m.2 PM981a does not support
HDMI output || support
Audio/3.5 Headphone Jack | Realtek ALCS1220A | Support
Memory | Kingston/Corsair DDR4 3200MHz | Support
USB|Supports most USB3.0 20 interfaces|backplane part 2.0 cannot be used
PS/2 interface|add driver VoodooPS2 test|unknown
Microphone | ALCS1220A | does not support use USB external connection

## Tips:
**The USB driver is customized under the MacPro7,1 model. If you need to use it, please set the third code as MacPro7,1**

**This theory is common to X570 models and is not guaranteed to be available, please test it yourself**

**It is recommended to add -v run code mode to boot-args for the first time installation to facilitate troubleshooting**

**For RX5000 6000 series graphics cards, please add agdpmod=pikera to boot-args**

**The three codes of the model have been deleted, please use the tool to add**

--
## Acknowledgments

**Acidanthera's OpenCore**

**Apple's macOS**

** AMD Vanilla's AMD Ryzen CPU Patch**
