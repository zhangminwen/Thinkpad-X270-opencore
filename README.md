# thinkpad-x270-opencore

# Supported OS
- [x] macOS 12.6.8 (Monterey)

# Laptop's Hardware
- <b>Model</b>: Thinkpad X270 (20HN，使用20HM安装Monterey的时候，能显示出Wi-Fi，但连接Wi-Fi就会重新开机)
- <b>CPU</b>: Intel Core i5-7200U 2 x 2.5 - 3.1 GHz, Kaby Lake
- <b>GPU</b>: Intel HD Graphics 620
- <b>RAM</b>: 8 GB 2400MHz DDR4
- <b>Screen</b>: 12,5" (1920x1080)
- <b>Wi-Fi</b>: Intel Dual Band Wireless-AC 8265
- <b>Camera</b>: 720p
- <b>Battery</b>: 3-cell with inside battery 

# Bios settings

<b>Security</b>
- `Security Chip` **Disabled**
- `Memory Protection -> Execution Prevention` **Enabled**
- `Virtualization -> Intel Virtualization Technology` **Enabled**
- `Virtualization -> Intel VT-d Feature` **Enabled**
- `Anti-Theft -> Computrace -> Current Setting` **Disabled**
- `Secure Boot -> Secure Boot` **Disabled**
- `Intel SGX -> Intel SGX Control` **Disabled**
- `Device Guard` **Disabled**


<b>Startup</b>
- `UEFI/Legacy Boot` **UEFI Only**
- `CSM Support` **No**


# 下面这些功能都能正常工作
- [x] Intel HD 620 Graphics (incuding graphics acceleration)
- [x] CPU Power Management
- [x] Battery
- [x] All USB ports
- [x] HDMI port (including HDMI Audio)
- [x] Intel Ethernet port
- [x] Audio
- [x] Trackpad (gestures work but not the trackpad click. tap to click works.)
- [x] Shutdown / Reboot 
- [x] Keyboard (incuding all fn Keys)
- [x] Wi-Fi
- [x] iMessage, FaceTime, App Store, iTunes Store (with valid smbios)
- [x] DRM support (iTunes Movies, Apple TV+, Amazon Prime and Netflix, and others)
- [x] Sleep / Wake (lid sleep and lid wake) (works for me you can try for yourself)
- [x] Internal camera (including Facetime)
- [x] Bluetooth (I will try to fix that)

# 下面这些功能不能正常工作
- [x] airdrop
- [x] macOS 12.6.8之前的Monterey系统休眠再进入系统后，Bluetoothd对应的进程cpu占用率达到100%，EFI中也添加了BlueFixup，升级到macOS 12.6.8就没有这个问题了