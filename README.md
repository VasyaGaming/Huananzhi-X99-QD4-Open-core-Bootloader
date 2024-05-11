![Screenshot 2024-04-06 at 8 05 06 AM](https://github.com/VasyaGaming/Huananzhi-X99-QD4-Open-core-Bootloader/assets/143002057/b8a59696-eb2b-4361-8167-37c528ba1928)
-------------------------------------------------
Open core For Huananzhi X99 QD4

Motherboard-Huananzhi X99 QD4

Processor-Intel Xeon E5-2670V3

SSD-Goodram cl100

Video Card-Amd RX570 8GB

--------------------------------------------------
Kexts used: 

 AppleALC.kext
 
 CpuTscSync.kext
 
 Lilu.kext
 
 RealtekRTL8111.kext
 
 RestrictEvents.kext
 
 SMCSuperIO.kext
 
 SMCProcessor.kext
 
 USBToolBox.kext
 
 UTBDefault.kext
 
 VirtualSMC.kext
 
 WhateverGreen.kext
 
 XHCI-unsupported.kext

---------------------------------------------------
What works

macOS Sonoma, Ventura, Big Sur, Catalina and macOS Monterey

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
