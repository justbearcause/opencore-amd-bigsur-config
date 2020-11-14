# opencore-amd-bigsur-config
OpenCore-based configuration for Gigabyte B450 I Aorus Pro WiFi + AMD Ryzen 5 2600 + MSI Radeon RX560

![Screenshot](https://i.imgur.com/t0rcchJ.png)

## 📝 Specs:
* **Motherboard:** Gigabyte B450 I Aorus Pro WiFi
* **Processor:** AMD Ryzen 5 2600
* **Video Card:** MSI Radeon RX560
* **RAM:** 2x16Gb 3200MHz DDR4 Hyper-X

## ✅ What's working:
* **Video output** using MSI Radeon RX560 with full hardware acceleration
* **Audio output** via Display Port using MSI Radeon RX560
* **Audio output** using on-board Realtek ALC 1220 (worked well in Catalina, but I didn't test it in Big Sur)
* **Ethernet** using on-board Intel I211 Gigabit Network Connection (worked well in Catalina, but I didn't test it in Big Sur)
* **Wi-Fi** using on-board Intel Wireless AC-9260. Connection and usability is Ok but speed is meh
* **Bluetooth** using on-board Intel Wireless AC-9260 Bluetooth Adapter. Discovers very few devices, got audio output working, but no input
* **Sleep**
* **Handoff**
* **Universal Clipboard**

## ❌ What's not working:
* **iMessage** and **FaceTime** and I don't know why. Login just fails quietly with no error
* **Apple Hypervisor**, of course

## 🚀 Bootloader and Drivers
* **OpenCore** v.0.6.3-RELEASE
* **OpenCanopy**
* **HFSPlus**

## ⚙️ Kexts:
* **Itlwm** v1.2.0-DEBUG-alpha
* **AirportItlwm** Big_Sur-v1.2.0-DEBUG-alpha
* **IntelBluetoothFirmware** v1.1.2
* **IntelBluetoothInjector** v1.1.2
* **AppleALC** v1.5.4-DEBUG
* **AppleMCEReporterDisabler** from AMD_Vanilla repo by AMD-OSX
* **SmallTreeIntel82576** v1.3.0 from SmallTree-I211-AT-patch repo by khronokernel
* **VirtualSMC** v1.1.8-DEBUG
* **WhateverGreen** v1.4.4-DEBUG
* **Lilu** v1.4.9-DEBUG
