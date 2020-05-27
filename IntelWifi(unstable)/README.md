# Apple Intel Wifi for Intel Dual-Band AC8265 (in development)
1. Copy kext to somewhere (dont put in /L/E or /S/L/E)
2. Right click on this kext and choose "Show Package Contents"
3. On "Contents" folder, Edit Info.plist
	search for "Wifi name" and replace it with your wifi name
	search for "Wifi password" and replace it with your wifi password.
Save the file!
4. Run this command
	cd "location of folder contains kexts"
	sudo chown -R root:wheel AppleIntelWiFi.kext
	sudo kextload AppleIntelWiFi.kext
5. System Preferences > Networks > Wifi -> turn it on
6. Enjoy your wifi.