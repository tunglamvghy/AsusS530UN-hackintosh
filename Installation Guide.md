# INSTALLATION GUIDE

1. Make a recovery USB using [**gibMacOS**](https://github.com/corpnewt/gibMacOS)
2. Copy **OC** folder and **Boot** folder to EFI partition of your USB.
3. Turn all Debug options for OC including

| Property | Value |
| - | - |
| ScanPolicy | 0 |        
| ApplePanic | True |
| AppleDebug | True |
| Display Level | 2147483650 |
| Target | 0x43 |

Add '-v' to boot-args

4. Boot to Mac Recovery using usb you have just made
5. Turn on Wifi and install macOS on your SSD.
6. Boot to macOS you've installed
7. Using [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) or **OpenCore Configurator** to generate new SMBIOS
8. Copy **OC** folder and **Boot** folder from EFI partition of your USB to EFI partition of your SSD.
9. Go to Post-installation folder, and install AsusSMCDaemon and ComboJack.
10. Restart and Enjoy your new hackintosh

***Notes:*** 
    
- *Change OpenCanopy background*
    1. You need a really big image! It seems this follows the same rules as any retina image, so you need an image double your resolution (3840x2160)
    2. Change the image to *PNG format*, rename it to *ModernBackground.png*
    3. Get [*chris1111/Icnspack-Builder*](https://github.com/chris1111/Icnspack-Builder) and install then launch the app.
    4. Click run. Drop your image on Icnspack-Builder. Click ready. Click save and save it somewhere.
    5. You should now have a resources.zip folder. Unzip that thing!
    6. Inside the folder should be Background.icns, put that into EFI/OC/Resources/Image
    7. Reboot and make sure it works
    
- *Turn on HiDPI for FullHD screen:* [**HiDPI**](https://github.com/tunglamvghy/AsusS530UN-hackintosh/tree/master/Post-installation/HiDPI)


- If your pc has different specs, try to read [**OpenCore guide**](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf) or [**Dortania guide**](https://dortania.github.io/OpenCore-Desktop-Guide/installer-guide/) for more details

## Need help. Contact me
[![Telegram](https://img.shields.io/badge/Chat_on-Telegram-blue.svg)](https://t.me/tunglamvghy)
***If you want me to create your own EFI with a little payment, contact me via Telegram.***

## [Donate me](https://paypal.me/vtlam98)
If you want to donate, send me via [**PayPal**](https://paypal.me/vtlam98)
