# MaximusXIIIHero-11900k-EFI

EFI Folder for my Hackintosh Builds

## Hardware Setup
- Motherboard: Asus Maximus XIII Hero
- CPU: Intel i9-11900k (Rocket Lake - spoofed to Comet Lake)
- RAM: 64gb Corsair Dominator Platinum
- GPU:
  - (1) Nvidia 3080Ti (Windows)
  - (2) XFX Radeon RX580 (macOS)
- Internal Drives (all 1TB each - listed in order of mobo m.2 slots)
  - Samsung 980 Pro (Windows)
  - WD_BLACK SN850X (new drive)
  - WD_BLACK SN850 (macOS Big Sur 11.6.7)
  - Samsung 980 Pro (exfat storage drive)


## Boot Loader
- OpenCore 0.9.6 (DEBUG)

## ACPI
- SSDT-EC
- SSDT-PLUG
- SSDT-PMC
- SSDT-AWAC
- SSDT-RHUB

## Drivers
- OpenHfsPlus.efi (I use HfsPlus.efi for BigSur)
- OpenCanopy.efi
- OpenRuntime.efi

## Kexts
- Lilu
- VirtualSMC
- WhateverGreen
- AppleALC
- NVMeFix (disabled on Big Sur but using for Ventura/Sonoma)
- FakePCIID
- USBMap (Custom made using USB Mapper)
- SMCProcessor
- SMCSuperIO
- CpuTscSync
- TSCAdjustReset
