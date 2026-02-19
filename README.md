# Raspberry Pi boot animation on LineageOS
Here's my stupid idea to have different booting animation for my KonstaKang [LineageOS](https://konstakang.com/devices/rpi5/LineageOS23/) powered raspberry pi.

![Screenshot](/boot/part0/000.png)

## Step how to USE
### Requirement:
- the KonstaKang Android itself (**Developer Mode** enabled).
- USB Debugging enabled.
- A USB Data cable or good WIFI.

### How to Install ADB
- Debian/Ubuntu-based Linux users can type the following command to install ADB:

  `sudo apt-get install android-sdk-platform-tools`
- Fedora/SUSE-based Linux users can type the following command to install ADB:
  `sudo dnf install android-tools`
  
---
## How to use:
1. Plug your Pi to your computer (Use the power port)
2. Make sure your Raspberry Pi turned on.
3. Authicate your Raspberry Pi
4. After that, open your computer then type `adb devices`
