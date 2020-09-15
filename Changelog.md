# CHANGELOG
**2020/09/15**
- Update OC to v0.6.2
- Update kexts, ACPI for AsusSMC
- Optimised config for OC 0.6.2
- Fix boot issue.

**2020/09/06**
- Update to macOS 11 BigSur Beta 6
- Update **pre-release AsusSMC kext** (thanks to @hieplpvip) with ***2 new features***:

        ▪ Battery Threshold (set default at 80%) => enable in Battery Setting > Battery Health...
        ▪ Add Fan speed
- Change from SSDT-DATA to CPUFriendProvider.kext
- Fix sleep issue
- Remove unused driver, ACPI files, optimised...
- Update OpenCore to latest commit
- Update kexts

**2020/08/20**
- Update to macOS 11 BigSur Beta 5
- Update OpenCore to latest commit
- Update kexts
- Disable Intel Wifi testing by default because of unstable (enable in config.plist)

**2020/08/13**
- Update OpenCore to latest commit.
- Customize OpenCanopy

**2020/08/07**
- Update to macOS 11 BigSur Beta 4
- Update OpenCore to v0.6.1
- Update kexts
- Update Intel Wifi testing (HeliPort and itlwm)

**2020/07/18**
- Fix SMCBattery kext and remove ACPIBatteryManager
- Update OpenCore, kexts
- Update Intel Wifi testing (HeliPort and itlwm)

**2020/07/14**
- Improve performance
- Fix bugs
- Disable Intel WiFi testing by default (enable it manually in ***config.plist***)

**2020/07/12**
- Update to macOS 11 BigSur Beta 2
- Update to latest version of OpenCore, Lilu, Whatevergreen, VirtualSMC
- Intel Wifi testing with Heliport and itwlm thanks to @[OpenIntelWireless](https://github.com/OpenIntelWireless) *(enabled by default in config.plist)*
(Extract *Heliport.app* in Wifi folder to Application and open it to connect Wifi)
- Working as normal.

**2020/07/08**
- **Update to macOS 11 BigSur**
- Update OpenCore to 0.6.0 develop vesion (can update to BigSur from macOS 10.15)
- Update kexts
- Use ACPIBattery (bugs with BatterySMC in BigSur)
- All working as normal

**2020/05/27**
- Update OpenCore to 0.5.9
- Update Kexts
- Update macOS to vesion 10.15.5
- Add Intel Wifi kext for who wants to try to use Intel AC8265 Dual-Band Wifi card.

**2020/05/03**
- Fix AsusSMC with Fn function (all working again)
- Fix Touchpad not working on some situation
- Fix inject VoodooI2C and VoodooPS2 in OpenCore (delete these kexts in /L/E or disable them in config.plist)
- Disable OpenCanopy and BootChime by default (enable in config.plist)

**2020/04/12**
- Add GUI for OpenCore by OpenCanopy
- Add startup sound (manually enable in config.plist)
- Optimized. Remove some unused things.
- Fixed DRM
- Known issues: Sometimes lost sound after booting to Windows and come back MacOS (try to hard-reset your PC to make sound working again)

**2020/04/09**
- Update OpenCore to v0.5.8 (newest config)
- Update kexts
- Fix boot issues related to IGPU after update to MacOS 10.15.4 (completely fixed)
- Known issues: Sometimes lost sound after booting to Windows and come back MacOS

**2020/04/02**
- Update kexts
- Fix boot issues related to IGPU after update to MacOS 10.15.4

**2020/03/16**
- Update OpenCore to v0.5.6
- fix boot error after update OpenCore
- known bugs: cant load VoodooI2C and VoodooPS2Controller from OpenCore. Just install those kext to /L/E and rebuild cache using Hackintool.

**2020/02/21**
- Update Kexts
- Replace USBInjectAll.kext with USBMap.kext

**2020/02/08**
- Edit ACPI to make AsusSMC kext work
- Fix Keyboard Backlight
- Fn function list:
  + Fn + F1: Mute
  + Fn + F2/F3: Increase/Decrease volume
  + Fn + F4/F5: Increase/Decrease screen brightness
  + Fn + F6: On/Off Touchpad
  + Fn + F7/F8: Increase/Decrease Keyboard Backlight (16 levels)
  + Fn + F9/F10/F11/F12: Home/End/PgUp/PgDown
  + Fn + Space: Play/Pause
  + Fn + Enter : Put Computer to Sleep (run install_daemon.sh as root to make this work)
  + Fn + Esc: On/Off Screen
- Add firmware Bluetooth (can use Intel Bluetooth)
- Sound fixing completely
- Update OpenCore to version 0.5.5
- Update all Kexts to newest version
* waiting for Wifi Intel Dual-Band AC8265 working

**2019/12/06**
- Update OpenCore to version 0.5.4
- Update Kexts to newest version
- Fix kernel panic when use Whatevergreen 1.3.6

**2019/11/18**
- Stable on macOS 10.15.1
- Stop update Clover (moved completely to OpenCore)
- Update OC Bootloader
- Update Kexts to newest version
- Fix sound not working
- Remove kext USB Wifi (just use setup file from homepage)
  + macOS 10.15: Use Hackintool to mount /System then run setup file

**2019/09/17**
- Make OpenCore Bootloader as Main Bootloader
- Update OpenCore Bootloader, kexts
- Add íntalling driver USB Wifi Comfast CF-811AC instruction

**2019/08/27**
- Add OpenCore Bootloader (testing)
- Fix Apple ALC
- Fix Minor bugs

**2019/06/14**
- Initialized
