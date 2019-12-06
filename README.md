
# Hackintosh for XiaoMI Gaming Laptop - 2018 version

- SUPPORT: macos 10.13 - 10.15

- CPU: Coffee Lake

## What's Working 

- Native power management (Using config of MacBook 15, Mid-2018 version) 

- Intel UHD 630 with metal support

- Audio with HiFi headphones amplifier (AppleALC & codecommander) 

- TrackPad (working as MagicTrackpad) 

- Type-C video with 4k support 

- USB 3.0 

- Brightness key 

- Built-in camera 

## What's Not Working 

- Intel Wifi and Bluetooth 

- Nvidia GPU (has been disabled in DSDT in order to save power) 

- Built-in mic (sometimes it works but sometimes not)

## Pre Works in BIOS

- Disable CFG Lock (MSR 0xE2 register written protection Lock)

- Set DVTM to 64 MB