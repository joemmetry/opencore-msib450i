# MSI B450I Chipset + AMD Zen2 OpenCore EFI

### [日本語](https://github.com/joemmetry/opencore-msib450i/blob/master/README.md)

EFI Folder for OpenCore Bootloader.
Created with the help of [OpenCore Vanilla Desktop Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/).

<img src="https://scontent.fmnl17-2.fna.fbcdn.net/v/t1.6435-9/206743122_10216513288344107_3539624459220602424_n.jpg?_nc_cat=109&_nc_rgb565=1&ccb=1-3&_nc_sid=0debeb&_nc_ohc=GIahA9UCavwAX-0qNjY&_nc_ht=scontent.fmnl17-2.fna&oh=26a8b3847e6d7f8eaf644a7e4826a00f&oe=60F11940"/>

### Features

- Latest AMD-OSX patches
- Support up to macOS 12 Beta 1
- Intel Wi-Fi and Bluetooth is fully working
- GUI boot menu enabled
- Triple-boot (macOS, Windows, Ubuntu)
- Bootcamp works

### Software Versions

- macOS Monterey Beta 1 (21A5248p)
- Windows 11
- Ubuntu 21.04
- OpenCore 0.7.2

### System Components

| **Component**       | **Model**                                  |
| ------------------- | ------------------------------------------ |
| CPU                 | AMD Ryzen 5 3600                           |
| Motherboard         | MSI B450I Gaming Plus AC                   |
| RAM                 | 16GB (2 x 8GB) Corsair Vengeance @ 3200MHz |
| Audio               | Realtek ALC887 Codec                       |
| GPU                 | AMD Radeon RX 580 8GB                      |
| Wi-Fi and Bluetooth | Intel Dual Band Wireless-AC 3168           |
| Ethernet            | Realtek RTL8111                            |
| OS Disk (SSD)       | ADATA XPG SX8200 PRO 512 PCIe NVMe         |

### Working

CPU, RAM, Fans, Cooling etc. ✔<br/>
Audio ✔<br/>
Ethernet ✔<br/>
Graphics ✔<br/>
HDMI ✔<br/>
Sleep/wake Function ✔<br/>
Power Management ✔<br/>
App Store ✔<br/>
iMessage ✔<br/>
iCloud ✔<br/>
FaceTime ✔<br/>
USB ✔<br/>
Bootloader ✔<br/>
HDMI Audio ✔<br/>
Volume Hotkeys ✔<br/>
Wi-Fi ✔<br/>
Bluetooth ✔<br/>
HandOff ✔<br/>

### Not Working

AirDrop ✗<br/>
Side Car ✗<br/>
Docker (only Docker machine works) ✗<br/>

### Quick Notes

1. Kernel extensions are not included in this repo. Go to [acidanthera](https://github.com/acidanthera), [OpenIntelWireless](https://github.com/OpenIntelWireless), and other providers to download the latest versions.
2. There are some macOS functions that aren't working because of limited Apple support.
3. This repo is just for learning how to configure your own EFI, simply copying this and putting in the EFI partition will not make the system boot properly.

### Sources

- [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [AMD Vanilla OpenCore](https://github.com/AMD-OSX/AMD_Vanilla)
- [OpenCore EFI and Kexts](https://dortania.github.io/builds/)
