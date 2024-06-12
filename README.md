# TWRP Device tree for Poco X6 5G

[![SourceForge Total Downloads](https://img.shields.io/sourceforge/dt/orangefox-device-xiaomi-rock?style=social&logo=sourceforge&logoColor=%23000000)](https://sourceforge.net/projects/premiumprjktrom/files/Garnet/Recovery/PBRP_4.0_garnet-Unofficial.img/download)

Poco X6 5G (codenamed _"garnet"_) is a smartphone from Xiaomi.

It was announced & released on Januari 2024.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Qualcomm SM7435-AB Snapdragon 7s Gen 2 (4 nm)
CPU     | Octa-core (4x2.40 GHz Cortex-A78 & 4x1.95 GHz Cortex-A55)
GPU     | Adreno 710
Memory  | 12GB RAM
Shipped Android Version | 13.0 with MIUI 14 for Poco
Storage | 256GB
Battery | 5100 mAh, non-removable
Display | AMOLED, 68B colors, 120Hz, Dolby Vision, 500 nits (typ), 1200 nits (HBM), 1800 nits (peak), 6.67 inches, 107.4 cm2 (~89.7% screen-to-body ratio), Corning Gorilla Glass Victus.
Camera  | 64 MP, f/1.8, 25mm (wide), 0.7µm, PDAF, OIS, 8 MP, f/2.2, 118˚ (ultrawide), 1/4.0", 1.12µm, 2 MP, f/2.4, (macro)

## Device picture

![poco_x6_5g](https://github.com/DeandraAir/android_device_xiaomi_garnet-pbrp/assets/142644567/094319f6-b3b6-4f91-9464-adc604838d5f)

## Features

Works:

- [X] ADB
- [X] Decryption
- [X] Display
- [X] Flashing
- [X] MTP
- [X] Sideload
- [X] USB OTG
- [X] Touch
- [X] Vibrator
- [X] Flashlight

# Building
```bash
source build/envsetup.sh
lunch twrp_garnet-eng
mka recoveryimage
```

## To use it:

```
fastboot flash recovery out/target/product/garnet/recovery.img
```
