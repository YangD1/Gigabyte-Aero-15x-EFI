## [Progress](https://github.com/bykaii/NOTE/issues/28) Language is Chinese.
> Notice: This is a backup configuration for me, please do not use it directly.This is a dual system configuration, please delete unwanted files as needed, such as `Microsoft`.
## Device
```
- Processor: i7-8750H
- Memory: 16GB 2666 MHz DDR4 (Upgraded, original was 8GB)
- Panel: LCD FHD 144Hz 1920x1080 IPS
- Graphics: Intel UHD Graphics 630 + NVIDIA GeForce GTX 1070 GDDR5 8GB

I/O | Ports:

- 3x USB 3.1 Gen1 (Type-A)
- 1x Thunderbolt™ 3 (USB Type-C)
- 1x HDMI 2.0
- 1x mini DP 1.4
- 1x 3.5mm Headphone/Microphone Combo Jack
- 1x SD Card Reader
- 1x DC-in Jack
- 1x RJ-45

Misc:
- Internal Speaker
- HD Camera
```
### Notes:
- Intel WiFi/Bluetooth card need to be replaced with a compatible one. (Used here: **Broadcom BCM94352Z**)
- EFI based

## How to use this repository:
- Root folder has the version of Hackintosh (10.14.2 or later - Mojave. Now is 10.14.4)

Then, inside each folder:
- EFI/CLOVER: Clover EFI files (with kexts, configs, patches, etc.)
- Library/Extensions: Has the kext files that needs to be put in your Library/Extensions folder
- patches: Has the used SSDT/DSDT patches for this version

## Working

**USB Based Devices**
- [x] All USB ports (2.0 + 3.0)
- [x] Keyboard (2.0)
- [x] Bluetooth (Internal 2.0)

**Network**
- [x] Ethernet card
- [x] WiFi + Bluetooth

**Power**
- [x] CPU power management
- [x] Battery indicator
- [x] USB PM
- [x] Sleep/Shutdown/Sleep/Restart

**Graphics**
- [x] Intel graphics card
> Since the HDMI interface is a discrete graphics output, it is temporarily unavailable on the Mojave platform.

**Misc**
- [ ] Sound (internal speakers + mic jack on/off)
- [ ] Touchpad
> Emmmm.I use trackpad 2.

## Not working/Issues
- [ ] NVIDIA graphics
- [ ] Thunderbolt 3
> Can use thunderbolt port expand second screen

### For reference only, not guaranteed to be fully available
