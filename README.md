# Hackintosh-Dell-Vostro-5590
EFI folder for OpenCore 0.7.9 and Monterey compatible with the Dell Vostro 5590 and 5490.


### Specs:
Type | Details
| -------------- |:----------------------------:|
CPU | Intel Core i7-10510U
iGPU | Intel UHD 620
dGPU | NVIDIA GeForce MX250
Display | 1920x1080
RAM | 24GB
Audio | Realtek ALC3204/236
WLAN | Intel 9462AC
LAN | Realtek RTL8169
SSD | 480GB Patriot Burst- macOS boot
NVMe | 256GB Samsung PM991 - Windows
KB | Built-in Standard PS2 Keyboard
TP | Built-in I2C HID Trackpad
SMBIOS | MacBookPro16,4
Bootloader | OpenCore 0.7.9

### What works and What doesn't or WIP:

- [x] ALC3204/236 Internal Speakers
- [x] ALC3204/236 Native Jack Output
- [x] All USB Ports Type A (2xUSB 3.0 and 1xUSB 2.0)
- [x] SpeedStep / Sleep / Wake
- [x] I2C Touchpad
- [x] Intel Bluetooth Module
- [x] Realtek RTL8169 LAN
- [x] USB Cardreader
- [x] ACPI Battery
- [x] Wi-Fi (on Monterey)

- [ ] DisplayPort over Type-C (did not check)
- [ ] MX250 dGPU (Not supported)
- [ ] Internal / External Mic and Camera (Microphone won't work because of Intel Smart Sound, camera need to map usb's)
- [ ] Intel UHD 620 iGPU HDMI Output

## Important Notes:
- Generate your OWN SMBIOS
- Do not COPY & PASTE this and use on your installer or Mac disk's EFI Partition. This is to give you idea on what will work and a jump start to hackintosh this laptop.
- Fixes for current problems are appreciated.
