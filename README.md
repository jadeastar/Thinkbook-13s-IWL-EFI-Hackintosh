# Hackintosh EFI for First Generation Lenovo ThinkBooks

### macOS Version:
- macOS Big Sur

### OpenCore Version: 
- 0.7.2 (Stuck for the time being)

### Compatible ThinkBooks:
- Thinkbook 13s IWL (Designed for)
- Thinkbook 14s IWL (Quite possibly will work, upstream reports it does)

### My Hardware Configuration
| Hardware | Info |
| ------ | ------ |
| CPU | Intel(R) Core(TM) i5-8265U CPU @ 1.80GHz |
| MEMORY | 8 GB DDR4 |
| GRAPHICS | Intel UHD Graphics 620 |
| DISK | TBA |
| SOUND | Intel Cannon Point-LP High Definition Audio Controller |
| Network | Intel Cannon Point-LP CNVi |

### Hardware Status
| Name | Comment |
| ------ | ------ |
| Graphics Acceleration |TBD|
| Trackpad |Works in Installer|
| Keyboard |Works in Installer|
| Internal Speaker |Works in Installer|
| Internal Microphone |TBD|
| Headphone jack |TBD|
| USB Type-A |TBD|
| USB Type-C |TBD|
| Camera |TBD|
| Battery Indicator |TBD|
| Brightness |TBD|
| Wifi |Works in Installer|
| Bluetooth |TBD|
| HDMI |TBD|

### Known Issues
| Name | Comment |
| ------ | ------ |
| Sleep | Closing the Lid will not trigger sleep, and leaving the lid open during manual sleep causes issues. Additionally the timed Turn Off Display option may cause issues. |
| Fingerprint |Doesn't work on Linux either, there is a effort for Linux drivers though.|

## Installation Instructions
Writing


Usefull Link and Credits:
- [OpenCore Install Guide]: this is starting point if you want to install Hackintosh using OpenCore.
- [Acidanthera]: for most of the kexts
- [Olarila]: If you want to download Mac Os Vanilla image without having Mac.
- [OpenIntelWireless]: for intel wifi & bluetooth kexts
- [VoodooI2C]: Trackpad kexts
- [ECEnabler]: for working battery status


[GenSMBIOS]: <https://github.com/corpnewt/GenSMBIOS>
[ProperTree]: <https://github.com/corpnewt/ProperTree> 
[OpenCore Install Guide]: <https://dortania.github.io/OpenCore-Install-Guide/>
[Olarila]: <https://www.olarila.com>
[OpenIntelWireless]: <https://github.com/OpenIntelWireless>
[Acidanthera]: <https://github.com/acidanthera>
[VoodooI2C]: <https://github.com/VoodooI2C/VoodooI2C>
[ECEnabler]: <https://github.com/1Revenger1/ECEnabler>
[ws839750375]: <https://github.com/ws839750375>
