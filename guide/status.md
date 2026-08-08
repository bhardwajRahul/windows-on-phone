<img align="right" src="https://github.com/n00b69/woa-lisa/blob/main/lisa.png" width="350" alt="Windows 11 running on a lisa">

# Running Windows on the Xiaomi 11 Lite NE 5G

# Project status

- Current **Driver** version: v2606.08
- Current **UEFI** version: v2606.08


# Simple status

| Feature                | Notes                                           | Status         |
|------------------------|-------------------------------------------------|----------------|
| 🔊 Audio               |                                                 | ✅            |
| 🔋 Battery             |                                                 | ✅            |
| 🎆 GPU                 | Experimental. There will be some artifacts when navigating through menus, and the device may occasionally reboot                                                | ✅            |
| 👆 Touch               | 10-point Multi-touch                                                | ✅            |
| 🪵 USB                 |                                                 | ✅            |
| 🔌 Charging              |                                           | ✅            |
| 💾 SD card                 | Windows cannot be installed on an SD card, but SD cards work in Windows. SDXC cards do not work when inserted in a running system, boot to Android with it inserted, then switch to Windows  | ✅            |
| 🔵 Bluetooth           |                                                 | ✅            |
| 🌐 Wi-Fi                |                                                 | ✅            |
| 📶 Cellular services       | SIM card must be in SIM1, calling does not work             | ✅            |
| ⌨️ Side buttons        |                                                 | ✅            |
| 🛡️ Security                 | Partial                                    | ⚠️            |
| 🛰️ GPS                 |                                                 | ✅            |
| 🧭 Sensors              |                                                 | ✅            |
| 📳 Vibration motor     |                                                 | ✅            |
| 🔦 Flashlight          |                       | ❌            |
| 💽 Virtualization              | Only WSL 1                                                | ❌            |
| 📷 Camera              |                                                 | ❌            |


# Detailed status

## 🔊 Audio

| Feature                | Notes                                       | Status         |
|------------------------|---------------------------------------------|----------------|
| 🔉 Bottom speaker       |                                             | ✅            |
| 🔉 Top speaker    |                                             | ✅            |
| 🎙️ Internal top mic    |                                             | ❌            |
| 🎙️ Internal bottom mic |                                             | ❌            |


## 🎆 GPU

| Feature                | Notes                               | Status         |
|------------------------|-------------------------------------|----------------|
| 🔆 Brightness control  |                           | ✅            |
| 🎆 x64 emulation      |  Only in Windows 11                          | ✅            |


## 🪵 USB & Charging

| Feature                         | Notes                                                            | Status         |
|---------------------------------|------------------------------------------------------------------|----------------|
| 🪵 USB-Fn (Charging & MTP)   | **[Default]**                                                     | ✅            |
| 🪵 USB-Host (OTG)              | Some of the features are work in progress (USB Powerless Dongles) | ⚠️            |
| 🔌 Charging (USB)             | Slow charging only, only in USB-Fn mode                           | ✅            |


## 📶 Cellular services

| Feature                | Notes                               | Status         |
|------------------------|-------------------------------------|----------------|
| 📶 Cellular data (2G)   | SIM card must be in SIM1, unsupported in some regions      | ✅            |
| 📶 Cellular data (3G)   | SIM card must be in SIM1, unsupported in some regions      | ✅            |
| 📶 Cellular data (4G)   | SIM card must be in SIM1                    | ✅            |
| 📶 Cellular data (5G)   | SIM card must be in SIM1                    | ✅            |
| 📞 Cellular calls      |                                                 | ❌            |
| 💬 SMS                 | SIM card must be in SIM1                    | ✅            |


## 🌐 Wi-Fi

| Feature                | Notes                               | Status         |
|------------------------|-------------------------------------|----------------|
| 🌐 Wi-Fi (2.4 Ghz)   |                             | ✅            |
| 🌐 Wi-Fi (5 Ghz)     |                             | ✅            |
| 🌐 Wi-Fi (6 Ghz)     |                             | ✅            |
| 📡 Wi-Fi Direct      |                             | ✅            |


## ⌨️ Side buttons

| Feature                | Notes                                       | Status         |
|------------------------|---------------------------------------------|----------------|
| ⌨️ Volume up button       |                                                 | ✅            |
| ⌨️ Volume down button  |                                                 | ✅            |
| ⌨️ Power button               |                                                 | ✅            |


## 🛡️ Security

| Feature                | Notes                                       | Status         |
|------------------------|---------------------------------------------|----------------|
| 🛡️ TPM                 | Software-backed. Doesn't support versions below Windows 11 22H2, or above Windows 11 24H2 26100.7171 | ❌            |
| 🛡️ Security processor      | Unavailable                          | ❌            |
| 🔒 BitLocker      | Available but not recommended                              | ✅            |
| 🛡️ Secure Boot      |                           | ❌            |
| 🛡️ Windows Hello Biometrics      | Requires working fingerprint scanner                          | ❌            |


## 🧭 Sensors

| Feature                | Notes                                       | Status         |
|------------------------|---------------------------------------------|----------------|
| 🧭 Accelerometer       |                                             | ✅            |
| 🧭 Gyroscope           |                                             | ✅            |
| 🧭 Light sensor        |                                             | ❌            |
| 🧭 Magnetometer        |                                             | ✅            |
| 🧭 Proximity           |                                             | ✅            |
| 🧬 Fingerprint scanner |                                                 | ❌            |
| 🏷️ NFC                 |                                                 | ❌            |


## 🔦 Flashlight

| Feature                | Notes                                       | Status         |
|------------------------|---------------------------------------------|----------------|
| 🔦 Flashlight          |                      | ❌            |
| 📸 Camera flash          |                | ❌            |














