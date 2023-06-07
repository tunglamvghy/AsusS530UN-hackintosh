## Donate me
I'll try to keep this repo up-to-date BUT as a student, I need to pay a lot of fees: tuition fees, exam fees, house rent, food, etc.
Any donation would help me a lot!

| [**PayPal**](https://paypal.me/vtlam98) | **Momo** |
| - | - |
| <img src="https://github.com/tunglamvghy/AsusS530UN-hackintosh/raw/master/Screenshoot/paypal.png" width="150px" height="" /> | <img src="https://github.com/tunglamvghy/AsusS530UN-hackintosh/raw/master/Screenshoot/momo.jpg" width="150px" height="" /> |

***If you want me to create your own EFI with a little payment, contact me via Telegram.***

**List of my repo**
The list of made EFI was on [my profile page](https://github.com/tunglamvghy/tunglamvghy)


## Contact me
[![Telegram](https://img.shields.io/badge/Chat_on-Telegram-blue.svg)](https://t.me/tunglamvghy)

# Asus Vivobook S530UN
# Mac OS X 14.0 Sonoma Preview
***This EFI can be used for previous version of macOS (not recommended)***
![Alt text](https://github.com/tunglamvghy/AsusS530UN-hackintosh/raw/master/Screenshoot/os.jpeg)

# Specification
- **MainBoard:** Asus X530UN.
- **Processor:** Intel Core i5-8250U @ 1.6GHz (KabyLake-R)
- **Graphic:** 
  + Intel UHD620 (1536MB of dynamic memory (shared from the system))
  + NVIDIA GeForce MX150 2GB
- **Network:**
  + Wifi: Intel 8265/8275 M2 NGFF (802.11 AC (2x2)) (working unstable!!)
  + Ethernet: No
  + Bluetooth: V4.1 (working)
- **Audio:** Realtek ALC256 (working)
- **Touchpad:** ELAN 1300 (I2C) (working in Polling mode)
- **Storage**:
  + SSD Samsung M.2 SATA 256GB
  + HDD TOSHIBA 1TB
- **Keyboard**: Chiclet keyboard 
- **Card Reader**: microSD CardReader
- **WebCam**: VGA Web Camera
- **Battery**: 3 Cells 42 Whrs Battery

# WORKING:
- [x] **Graphics UHD 620**
- [x] Graphics NVIDIA GeForce MX150 **(NOT support now)**
- [x] **Sound**
- [x] **WiFi**
- [x] **Bluetooth** (broken in macOS 12 beta 10)
- [x] Apple Store
- [x] External USB headphone
- [x] USB 2.0
- [x] USB 3.0
- [x] Adjust brightness
- [x] **Fn feature** 
    + **Fn + F1**: Mute
    + **Fn + F2/F3**: Increase/Decrease volume
    + **Fn + F4/F5**: Increase/Decrease screen brightness
    + **Fn + F6**: On/Off Touchpad
    + **Fn + F7/F8**: Increase/Decrease Keyboard Backlight (16 levels)
    + **Fn + F9/F10/F11/F12**: Home/End/PgUp/PgDown
    + **Fn + Space**: Play/Pause
    + **Fn + Enter** : Put Computer to Sleep (run install_daemon.sh as root to make this work)
    + **Fn + Esc**: On/Off Screen
- [x] Led light keyboard (Fn + F7/F8: Increase/Decrease Keyboard Backlight (16 levels))
- [x] Sleep power
- [x] Battery with Battery Threshold feature (limit charging at 80% for a long-life battery) 
- [x] Trackpad (Only working in Polling MODE with VoodooI2C)
- [x] Full 4 cores
- [x] Temporature
- [x] System Fan Control
- [x] Disabling discrete graphics GPU with SSDT Patching
- [x] Ethernet (Using NullEthernet.kext)~~
- [x] Hardware Acceleration
- [x] Power Management and P-States
- [x] iCloud 

# KNOWN ISSUES


# INSTALLATION GUIDE
[See Installation guide](https://github.com/tunglamvghy/AsusS530UN-hackintosh/blob/master/Installation%20Guide.md)

# CHANGELOG
[See Changelog](https://github.com/tunglamvghy/AsusS530UN-hackintosh/blob/master/Changelog.md)

# SCREENSHOT
![Alt text](https://github.com/tunglamvghy/AsusS530UN-hackintosh/raw/master/Screenshoot/20230607.png)

## Credits
@RehabMan for his guide for beginner

@alexandred and his team for VoodooI2C

@acidanthera for his OpenCore Bootloader and kexts

@hieplpvip for his AsusSMC kexts

@OpenIntelWireless for his Intel Wifi support

@black.dragon74 for custom FAN control (see https://osxlatitude.com/forums/topic/10244-how-to-implement-custom-fan-control-on-asus-laptops/
and many more people that I can't list here.
