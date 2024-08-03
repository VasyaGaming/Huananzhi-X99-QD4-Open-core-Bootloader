HUANANZHI X99 QD4 + Intel® Xeon® E5-2670 v3 + AMD Radeon™ RX 570
![Screenshot 2024-04-06 at 8 05 06 AM](https://github.com/VasyaGaming/Huananzhi-X99-QD4-Open-core-Bootloader/assets/143002057/b8a59696-eb2b-4361-8167-37c528ba1928)
-------------------------------------------------
Open core For Huananzhi X99 QD4
-------------------------------------------------
Complete hardware specs

Motherboard Name: Huananzhi X99-QD4 | Motherboard Chipset: Intel Lynx Point - Q87, Intel Haswell-EP

CPU Type: 12-Core Intel® Xeon® E5-2670 v3, 2266 MHz

Memory: 1 X 8GB DDR4-2133 Reg. ECC DDR4 SDRAM - Micron

Video Adapter: AMD Radeon™ RX 570 (8176 MB) (Vendor Sapphire Nitro +)

Audio Adapter: Realtek ALC897 @ Intel Lynx Point PCH - High Definition Audio Controller

Ethernet Adapter: Realtek PCIe GbE Family Controller

Disk Drive: Goodram cl00 120GB

--------------------------------------------------
Kexts used: 

 AppleALC.kext
 
 CpuTscSync.kext
 
 Lilu.kext
 
 RealtekRTL8111.kext
 
 RestrictEvents.kext
 
 SMCSuperIO.kext
 
 SMCProcessor.kext
 
 USBMAP.kext

 VirtualSMC.kext
 
 WhateverGreen.kext
 

---------------------------------------------------
What works
macOS Sequoia, macOS Sonoma, Ventura, Big Sur, Catalina and macOS Monterey

Audio

HDMI/DP (in dGPU - Works OOB)

All USB ports

Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)

Temperature monitoring for everything

DRM content (Netflix, ATV+, Airplay 2 mirroring etc)

Shutdown/Reboot/Update to newer macOS builds over time

----------------------------------------------------
Bios settings Disable

Go to advanded -> ACPI settings -> ACPI sleep state -> disable

Go to advanded -> NCT55320 Super IO configuration -> Serial Port 1 -> serial port -> disable

Go to advanded -> CSM Configuration -> video -> change to UEFI -> disable

Reboot the machine

Go to advanded -> CSM Configuration -> CSM Support -> disable

------------------------------------------------------
Bios settings on 

1 Go to advanded -> USB Configuration -> XHCI Hand-off -> enable

2 Go to advanded -> USB Configuration -> EHCI Hand-off -> enable

3InterRCSetup -> Processor Configuration -> Hyper Threading -> enable

--------------------------------------------------------
