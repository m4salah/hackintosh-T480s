# macOS on Thinkpad T480s
# ** backlight not working if you solve the this issue please pull request the repo **

## My hardware configuration
| Name                | Specifications | Funtional or not |
| ------------------- | -----------------------------------------|---------------|
| Processor           | Intel Core i5-8250U Processor            |Fully|
| Memory              | 16GB-> 8GB on Bourd and 8GB on the slot                             |Fully|
| Storage             | INTEL SSDPEKKF256G8L Controller   256GB  |Fully|
| Graphics            | Intel UHD Graphics 620                   |Fully with WhateverGreen.kext and properties inject|
| Display             | 14.0" FHD 1920x1080 LED IPS              |Backlight not working|
| Audio               | Realtek Audio ALC257 codec               |Fully with AppleALC.kext and layout-id 11|
| Ethernet            | Intel(R) Ethernet Connection (4) I219-V  |Fully with IntelMausi.kext|
| WLAN & Bluetooth    | Intel(R) Dual Band Wireless-AC 8265      |Not Working, need to Replace, i use Tp-Link Nano|
| MicroSD Card Reader | Generic-SD/MMC CRW USB Device            |Fully with USBPorts.kext|
| Keyboard & Trackpad | LED backlight, TrackPoint and multi-touch touchpad |Almost fully with VoodooPS2Controller.kext, VodooSMBUS.kext and SSDT-Keyboard-X1C6 patch| 
| Fingerprint         | On chip fingerprint reader               |Non-funtional|
| Camera         | built in camera               |Working with USBInjectAll.kext|


All ports listed below are working.

|Ports |
|------|
| two USB 3.1 Gen 1|
|two USB 3.1 Type-C Gen 2/Thunderbolt 3|
|HDMI 1.4b|
|Ethernet extension connector|
|headphone/microphone jack [Headphone Problem that i faced](https://github.com/tylernguyen/x1c6-hackintosh/issues/36)|
|MircoSD card reader|


## Other Reasources

- https://github.com/kk1987/T480s-hackintosh
- https://github.com/tylernguyen/x1c6-hackintosh
- https://github.com/samuelshi/Thinkpad-T480S
- https://github.com/rtotheb2000/macOS-ThinkPad-T480s-catalina

  *All credit goes to all of those guys*
