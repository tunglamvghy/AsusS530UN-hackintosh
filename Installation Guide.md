# INSTALLATION GUIDE

1. Make installation device and install MacOS to your PC (follow this [*guide*](https://dortania.github.io/OpenCore-Desktop-Guide/installer-guide/) )
2. Download **OC** folder and **Boot** folder copy it to your **EFI** folder. To mount EFI partiton in Windows, use ***diskpart*** (Google it!!)
3. Edit **PlatformInfo** in **config.plist**:  [Generate new MacInfo](https://github.com/corpnewt/GenSMBIOS)
4. Set **"\EFI\Boot\Bootx64.efi"** or **"\EFI\OC\Bootstrap\Bootstrap.efi"** to be the first boot entry in **UEFI Setting**
5. Restart and enjoy your hackintosh

