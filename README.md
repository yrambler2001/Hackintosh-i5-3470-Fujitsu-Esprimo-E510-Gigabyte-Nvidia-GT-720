# Hackintosh-i5-3470-Fujitsu-Esprimo-E510-Gigabyte-Nvidia-GT-720

# Info PC

```
PC: Fujitsu ESPRIMO E510 E85+ SFF
CPU: Intel Core i5-3470
VGA: Gigabyte Nvidia GT 720 1GB
RAM: 20GB
SSD: 120GB
Bluetooth: Asus USB-BT400
```

# Hackintosh + OpenCore (Supported version: 0.5.7)

- https://dortania.github.io/OpenCore-Desktop-Guide

# Works

- Audio
- Ethernet
- Bluetooth
- GPU
- All USB ports

# Note

The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID into your code

```
<dict>
    <key>AdviseWindows</key>
    <false/>
    <key>MLB</key>
    <string>xxxxxxxxxxxxxxx</string>
    <key>ROM</key>
    <data>ESIzRFVm</data>
    <key>SpoofVendor</key>
    <true/>
    <key>SystemProductName</key>
    <string>iMac13,2</string>
    <key>SystemSerialNumber</key>
    <string>xxxxxxxxxxx</string>
    <key>SystemUUID</key>
    <string>xxxxxxxx-xxxxx-xxxxx-xxxx-xxxxxxxx</string>
</dict>
```
