# HP Elitebook 2560p High Sierra
Clover Configuration for config.plist, kext, acpi patch for HP Elitebook 2560p High Sierra

this is clover configuration bundle for HP Elitebook 2560p

## Specification
HP Elitebook 2560p
- Intel Core i5-2540M Sandy Bridge 2nd Gen
- Chipset Mobile Intel QM67 Express chipset
- Graphics Intel HD Graphics 3000
- Display 12.5-inch

## Confirm Work : All Works
- Bluetooth
- LAN
- Volume Control
- Graphics (native support)
- Display (native res & brightness control)
- Battery Status
- Sound
- Trackpad (small trackpad at this laptop)

- Intel Wifi Work with OpenIntelWireless 1.2.0 alpha

OS : High Sierra 10.13.6 (Olarila torrent version)

Build based on RehabMan [Guide] HP ProBook/EliteBook/Zbook using Clover UEFI hotpatch 
https://www.tonymacx86.com/threads/guide-hp-probook-elitebook-zbook-using-clover-uefi-hotpatch.261719/

## Important Files :
- clover/config.plist
- clover/acpi/patched/*
- clover/kexts/other/ACPIBatteryManager.kext

other files come from olarila installer

## Notes :
- Bluetooth lost after sleep
- please generate your own unique SMBIOS ID
- also do disable hibernate according to guide
- Increase VRAM Intel HD 3000 : https://github.com/ipang-dwi/ihd3000 (for 8GB ram i use 512 to 1024 v2 patch)
- Intel Wifi Works with OpenIntelWireless 1.2.0 alpha https://github.com/OpenIntelWireless (already included at clover kext folders)
copy itwlm (sierra ) and airport itwlm to clover kext other
- run with Heliport app


![Image 1](https://raw.githubusercontent.com/psetiawan/hpelitebook2560phighsierra/main/assets/Untitled1.jpeg)
![Image 2](https://raw.githubusercontent.com/psetiawan/hpelitebook2560phighsierra/main/assets/Untitled2.jpeg)
![Image 3](https://raw.githubusercontent.com/psetiawan/hpelitebook2560phighsierra/main/assets/Untitled3.jpeg)
![Image 4](https://raw.githubusercontent.com/psetiawan/hpelitebook2560phighsierra/main/assets/Untitled4.jpeg)

