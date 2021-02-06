# INSTALLATION GUIDE

1. Make a recovery USB using [**gibMacOS**](https://github.com/corpnewt/gibMacOS)
2. Copy **OC** folder and **Boot** folder to EFI partition of your USB.
3. Boot to Mac Recovery using usb you have just made
4. Turn on Wifi and install macOS on your SSD.
5. Boot to macOS you've installed
6. Using [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) or **OpenCore Configurator** to generate new SMBIOS
7. Copy **OC** folder and **Boot** folder from EFI partition of your USB to EFI partition of your SSD.
8. Restart and do **Adjust Power Mode for CPU**
9. Enjoy your new hackintosh

***Notes:*** 
- *Adjust PowerMode for CPU*
    1. Make sure you have good network
    2. Run the following command with Terminal
    ```bash
    bash -c "$(curl -fsSL https://raw.githubusercontent.com/stevezhengshiqi/one-key-cpufriend/main/one-key-cpufriend.sh)"
    ```
    3. Choose the power scheme
    4. Copy generated **CPUFriendDataProvider.kext** in Desktop and replace the old kext in /OC/Kexts
    5. Restart your Hackintosh
    If you change the SMBIOS, do all steps again.
    
- *Change OpenCanopy background*
    1. You need a really big image! It seems this follows the same rules as any retina image, so you need an image double your resolution (3840x2160)
    2. Change the image to *PNG format*, rename it to *ModernBackground.png*
    3. Get [*chris1111/Icnspack-Builder*](https://github.com/chris1111/Icnspack-Builder) and install then launch the app.
    4. Click run. Drop your image on Icnspack-Builder. Click ready. Click save and save it somewhere.
    5. You should now have a resources.zip folder. Unzip that thing!
    6. Inside the folder should be Background.icns, put that into EFI/OC/Resources/Image
    7. Reboot and make sure it works
    
- If your pc has different specs, try to read [**OpenCore guide**](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf) or [**Dortania guide**](https://dortania.github.io/OpenCore-Desktop-Guide/installer-guide/) for more details

## Need help. Contact me
[![Telegram](https://img.shields.io/badge/Chat_on-Telegram-blue.svg)](https://t.me/tunglamvghy)
[![Messenger](https://img.shields.io/badge/Chat_on-Messenger-0078FF)](https://m.me/k38b.lamtung)
***Due to COVID-19, now I have free time. So if you want me to create your own EFI with a little payment, contact me via Telegram.***

## [Donate me](https://paypal.me/vtlam98)
If you want to donate, send me via [**PayPal**](https://paypal.me/vtlam98)
