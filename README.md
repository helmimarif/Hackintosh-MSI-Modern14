# Hackintosh MSI Modern 14
<center> <img src="https://user-images.githubusercontent.com/106028948/206348026-af0592a7-f32e-4b25-aada-8646bf74e4fb.png" width="90%"></img> </center>

# Specs
- Model : B10MW
- Processor : Intel Core i3 10110U
- IGPU : Intel UHD Graphics 620
- Display : 13.9" FHD (1920x1080), IPS-Level
- RAM : 8GB DDR4 PC21300 (2667Mhz)
- Storage : SSD 512GB M.2 2242 NVME 3.0
- Wireless : Intel AC 9462 and Bluetooth (labeled as AC 9560)
- Audio : Realtek ALC235 (LayoutID : 29)
- Touchpad : I2C HID multitouch
- Keyboard : PS2 White backlight
- Camera : HD (30fps @ 720p)
- 1x Micro SD Card
- 2x Type-A USB3.2
- 1x Type-C (USB3.2 / DP)
- 1x HDMI (4K @ 30Hz)
- 1x Audio Jack

# Status
- OS : **macOS BigSur v11.7 (Build 20G817)**
- Bootloader : **OPENCORE r0.8.5**
- Bios Version : E14D1IMS.108
- Sata Mode : AHCI
- Intel Virtualization : Enabled
- VT-d : Enabled
- Boot Mode : UEFI
- Secure Boot : Disabled

# Working
- [x] CPU Power Management
- [x] QE/CI of Intel UHD Graphics 620
- [x] Wifi
- [x] Bluetooth
- [x] Internal Speaker, Headphone and Internal Microphone
- [x] Touchpad with macOS gestures
- [x] Keyboard
- [x] Keyboard Backlight & HotKeys
- [x] Brightness
- [x] Brightness Button Up / Down
- [x] Battery Indicator
- [x] Hardware sensors
- [x] All USB Port
- [x] Camera
- [x] HDMI Out
- [x] HDMI Audio
- [x] Restart, Sleep and Shutdown
- [x] Etc

# Not Working
- Appstore(this will be fixed if you generate SMBIOS)
- Airdrop (Bluetooth have time problem with connect to any ios devices)