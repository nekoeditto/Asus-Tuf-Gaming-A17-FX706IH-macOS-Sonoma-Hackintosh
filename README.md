![Asus Tuf Gaming A17 FX706IH macOS Sonoma Hackintosh](https://www.asus.com/media/global/gallery/trfp1kp4xvoudgam_setting_xxx_0_90_end_2000.png)
 ## Hardware Specs
 ### Basic info
- This is Asus Tuf Gaming A17 FX706IH-H7088
- BIOS version v316
### Specs:
  - CPU: AMD (Advanced Micro Devices) Ryzen 7 4800H
  - GPU: GeForce GTX 1650 (Notebook) 4Gb (dGPU - not working)
  - GPU: AMD (Advanced Micro Devices) RX Vega 7 (iGPU) 512Mb
  - Memory: 1 x 16Gb Samsung DDR4 3200MHz
  - Storage: Patriot P210 256Gb
  - LAN: RealTek rtl8111 Gigabit Network Connection
  - Wlan: RealTek rtl8822CE
  - Audio: RealTek ALC256 Audio Codec
    ## Configure BIOS Settings
  - Disable: **Secure Boot**
  - Set: **Opencore Boot Drive as 1st in boot menu**
    ## Tested OS 
   - macOS Catalina 10.15.7
   - macOS Monterey 12.6
   - macOS Ventura 13.2
   - macOS Sonoma 14.2
   ## Bootloader
   - OpenCore 0.7.9
   ## Kexts
   - AMDRyzenCPUPowerManagement.kext
   - AmdTscSync.kext
   - AppleALC.kext
   - AppleMCEReporterDisabler.kext
   - AsusSMC.kext
   - BrightnessKeys.kext
   - ECEnabler.kext
   - HoRNDIS.kext
   - Lilu.kext
   - NootedRed.kext
   - NVMeFix.kext
   - RadeonSensor.kext
   - RealtekRTL8111.kext
   - RestrictEvents.kext
   - SMCAMDProcessor.kext
   - SMCBatteryManager.kext
   - SMCRadeonGPU.kext
   - SMCSuperIO.kext
   - USBToolBox.kext
   - UTBMap.kext
   - VirtualSMC.kext
  ## Known Issues 
   - Wi-Fi/BT doesn't work bc RealTek adapter
   - Random exitbs: start on boot, fix in quirks (I think)
   - Internal Mic doesn't work, only external
   - iServices, fix in smbios (I think)
  ## Credits 
Thanks to [Nehul Tyagi](https://github.com/nehultyagi1) and [ASUS FA-706IH Laptop Hackintosh](https://github.com/Ragnarok93/ASUS-F17-Hackintosh)
