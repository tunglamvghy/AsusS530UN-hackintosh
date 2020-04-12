## [Donate me](https://paypal.me/vtlam98)
I'll try to keep this repo up-to-date BUT as a student, I need to pay a lot of fees: tuition fees, exam fees, house rent, food, etc.
Any donation would help me a lot!

# Asus Vivobook S530UN
# Mac OS X 10.15 Catalina
![Alt text](https://github.com/tunglamvghy/AsusS530UN-hackintosh/raw/master/Screenshoot/os.png)
# Specification
- **MainBoard:** Asus X530UN.
- **Processor:** Intel Core i5-8250U @ 1.6GHz (KabyLake-R)
- **Graphic:** 
  + Intel UHD620 (1536MB of dynamic memory (shared from the system))
  + NVIDIA GeForce MX150 2GB
- **Network:**
  + Wifi: Intel 8265/8275 M2 NGFF (802.11 AC (2x2)) <use USB Wifi Comfast CF-811AC instead>
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
- [ ] WiFi (Replace with USB Wifi or waiting for Intel Wifi firmware)
- [x] **Bluetooth** (fully supported)
- [x] Apple Store
- [x] External USB headphone
- [x] USB 2.0
- [x] USB 3.0
- [x] Adjust brightness
- [x] Fn feature 
    + Fn + F1: Mute
    + Fn + F2/F3: Increase/Decrease volume
    + Fn + F4/F5: Increase/Decrease screen brightness
    + Fn + F6: On/Off Touchpad
    + Fn + F7/F8: Increase/Decrease Keyboard Backlight (16 levels)
    + Fn + F9/F10/F11/F12: Home/End/PgUp/PgDown
    + Fn + Space: Play/Pause
    + Fn + Enter : Put Computer to Sleep (run install_daemon.sh as root to make this work)
    + Fn + Esc: On/Off Screen
- [x] Led light keyboard (Fn + F7/F8: Increase/Decrease Keyboard Backlight (16 levels))
- [x] Sleep power
- [x] Battery
- [x] Trackpad (Only in Polling MODE with VoodooI2C)
- [x] Full 4 cores
- [x] Temporature
- [x] Disabling discrete graphics GPU with SSDT Patching
- [x] Ethernet (Using NullEthernet.kext)~~
- [x] Hardware Acceleration (Not test yet)
- [ ] Personal Hotspot (Not test yet)
- [x] Power Management and P-States
- [x] iCloud 
- [ ] iMessage (Not test yet)
- [ ] Airdrop (Not test yet)
- [ ] AirPlay (Not test yet)
- [x] iBooks (Not test yet)
- [ ] HandOff (Not test yet)

# KNOWN ISSUES
- Waiting for Intel Wifi firmware (soon)

# SCREENSHOT
![Alt text](https://github.com/tunglamvghy/AsusS530UN-hackintosh/raw/master/Screenshoot/Screen%20Shot%202020-02-08%20at%2022.59.14.png)

## Credits
@RehabMan for his guide for beginner
@alexandred and his team for VoodooI2C
@acidanthera for his OpenCore Bootloader and kexts
@hieplpvip for AsusSMC kexts
@black.dragon74 for custom FAN control (see https://osxlatitude.com/forums/topic/10244-how-to-implement-custom-fan-control-on-asus-laptops/
and many more people that I can't list here.
