# Clover EFI For ACER Aspire E1-471g(-53234G50Mnks)


 - Intel Core i5-3230M 
 - ACER EA40_HC   ( HM77, Intel Ivy Bridge )
 - Memory 12.0 GB 1600 MHz DDR3
 - Intel(R) HD Graphics 4000
 - NVIDIA GeForce 710M (1 GB)
 - Realtek ALC269
 - Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter

---

#### Functional
- [X] CPU Turbo
- [x] Audio
- [x] Battery Management
- [x] Backlight
- [x] Wried Network
- [ ] Wireless Network
- [ ] Bluetooth
- [x] WebCam
- [ ] SDHCI
- [x] AppleUSBMouse
- [x] AppleUSBKeyboard
- [x] Fn



#### How To Use
Copy EFI folder to EFI desk.
If you were using UEFI, delete boot drivers32 drivers64 folder is recommend. 


#### Tools
  - [UniBeast](http://www.tonymacx86.com/resources/unibeast-6-2-0.314/)
  - [MultiBeast](http://www.tonymacx86.com/resources/multibeast-el-capitan-8-2-2.318/)
  - [Clover EFI bootloader](https://sourceforge.net/projects/cloverefiboot/)
  - [Clover Configurator](http://www.tonymacx86.com/resources/clover-configurator.276/)
  - [Maciasl](https://sourceforge.net/projects/maciasl/) (for change dsdt file)
  - [DarwinDumper](https://bitbucket.org/blackosx/darwindumper)


#### Kext And Reference From
  - [FakeSMC](http://www.hwsensors.com/releases)
  - [Voodoo-PS2-Controller](https://github.com/RehabMan/OS-X-Voodoo-PS2-Controller)
  - [USB-Inject-All](https://github.com/RehabMan/OS-X-USB-Inject-All)
  - [AppleALC](https://github.com/vit9696/AppleALC)
  - [HDAEnablers](https://github.com/Mirone/HDAEnablers)（DSDT injected layout-id, Not needed.）
  - [Codec-Commander](https://github.com/RehabMan/EAPD-Codec-Commander)
  - [ACPI-Battery-Driver](https://github.com/RehabMan/OS-X-ACPI-Battery-Driver)
  - [Intel-Backlight](https://github.com/RehabMan/OS-X-Intel-Backlight)（DSDT injected, Not needed.）
  - [Realtek-Network](https://github.com/RehabMan/OS-X-Realtek-Network)
  - [AnyiSightCam](https://github.com/javenxww/E1-471g-MAC-10.11.5-clover/tree/master/EFI/CLOVER/kexts/10.11/)
  - [Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config)
  - [Tonymacx86.com](http://www.tonymacx86.com/)
  - [javenxww/E1-471g-MAC-10.11.5-clover](https://github.com/javenxww/E1-471g-MAC-10.11.5-clover)
  - [holoto/ec-471g](https://github.com/holoto/ec-471g)
  - [Fix-Hotkey-Brightness](http://www.insanelymac.com/forum/topic/305030-guide-how-to-fix-brightness-hotkeys-in-dsdt/)


#### For More

  - [Clover-Wiki](https://clover-wiki.zetam.org)
  - [Speed-Up-Restart](http://www.yekki.me/speed-up-restart/) 
  - [Wireless-AR5B22](https://github.com/matthew728960/Clover-ACER-E1-471G/raw/master/Tools/AR5B22/IO80211Family.kext_AR9462_10.11.6.zip) (Buggy, see [install-mac-os-x-on-chromebook-c720](http://www.omgchrome.com/install-mac-os-x-on-chromebook-c720/)) 