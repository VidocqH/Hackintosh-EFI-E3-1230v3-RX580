# Hackintosh_E3-1230v3_RX580

## Computer Infomation
|Name|Model|
|----|----|
|CPU|Intel Xeon E3-1230 v3, 3700MHz|
|MotherBoard|ASRock B85 Pro4, Haswell|
|Memory|Kingston 12 GB 1600 MHz DDR3|
|Graphics|Radeon RX 580 (8 GB)|
|HardDisk|KINGSTON SA400S37240G (240 GB, SATA-III)<br>KINGSTON SV300S37A60G (60 GB, SATA-III)<br>ST1000DM003-9YN162 (1 TB, 7200 RPM, SATA-III)<br>ST500DM002-1CH14C (500 GB, 7200 RPM, SATA-III)|
|Audio|Realtek ALC892|
|Network|Broadcom 802.11ac Network Adapter<br>Intel(R) Ethernet Connection I217-V|

## <u>All the descriptions below are about the latest version of EFI</u>

For now, it is `EFI-11.4.0-OpenCore`.

## EFI Structure

+ OpenCore 0.7.1
+ ACPI
  + SSDT-EC-DESKTOP.aml
  + SSDT-PLUG-DRTNIA.aml
+ Kexts
  + Lilu.kext
  + VirtualSMC.kext
  + WhateverGreen.kext
  + IntelMausi.kext
  + NVMeFix.kext
  + SMCProcessor.kext
  + SMCSuperIO.kext
  + USBInjectAll.kext
  + RadeonBoost.kext
  + AppleALC.kext
+ Drivers
  + VBoxHfs.efi
  
## Known issues

  + Sleep wake failure
