# Flashable Firmware for OnePlus 13 (dodge)

[![Hits](https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2Fspike0en%2Fdodge_flashable_firmware&label=Hits&icon=github&color=%23b02a37&labelColor=2E2E3F)](https://github.com/spike0en/oplus_firmware_archive) 

[![Total Downloads](https://img.shields.io/github/downloads/spike0en/dodge_firmware_flasher/total?logo=github&logoColor=white&label=Downloads&color=007377)](https://github.com/spike0en/dodge_firmware_flasher/releases)
[![Latest Release](https://img.shields.io/github/release/spike0en/dodge_firmware_flasher?label=Latest&logo=git&logoColor=white&color=1E6091)](https://github.com/spike0en/dodge_firmware_flasher/releases/latest)

[![Stars](https://img.shields.io/github/stars/spike0en/dodge_firmware_flasher?logo=github&color=D4AF37)](https://github.com/spike0en/dodge_firmware_flasher/stargazers)
[![Contributors](https://img.shields.io/github/contributors/spike0en/dodge_firmware_flasher?logo=github&color=9B5DE5)](https://github.com/spike0en/dodge_firmware_flasher/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/spike0en/dodge_firmware_flasher?logo=github&color=468FAF)](https://github.com/spike0en/dodge_firmware_flasher/network/members)

## About

- A collection of **flashable firmwares** for **OnePlus 13** (`dodge`), supporting all regional variants (`IND` / `EEA` / `GLO` / `CN` / `NA`). 
- This script is helpful when flashing custom ROM builds that require a specific firmware version but do not ship the same in the build itself.
- Automatically flashes firmware to **both slots (A/B)**.  
- Includes **CN model auto-detection**, which flashes `oplusstanvbk.img` & `modem.img` from **ColorOS** to fix signal issues on `CN` units running **OxygenOS**.  
- Safe to use — does **not wipe or modify user data**.  
- Firmware images are sourced from [oneplus_archive](https://github.com/spike0en/oneplus_archive) and repacked into a compatible flashable template.  


## Partitions

The following partition images are flashed to **both slots (A/B)**:

```sh
abl, aop_config, aop, bluetooth, cpucp, cpucp_dtb, devcfg, dsp, engineering_cdt, featenabler, hyp, imagefv, keymaster, modem, oplus_sec, oplusstanvbk, pdp, pdp_cdb, pvmfw, qupfw, shrm, soccp_dcd, soccp_debug, splash, spuservice, tz, uefi, uefisecapp, xbl_config, xbl_ramdump, xbl, boot, init_boot, vendor_boot, dtbo, vbmeta_system, vbmeta_vendor
```

## Flashing Procedure

1. Download the firmware zip file corresponding to the target Oxygen OS or Color OS version (check the file name) from the download link given below.
2. The firmware zip file can be directly flashed from a custom recovery like OrangeFox/TWRP.
3. It doesn't matter which firmware version you are on or if you are on a custom or stock ROM; you can just flash or sideload the firmware file.
4. The script will automatically flash the firmware to both slots, so there's no need to flash it twice!
5. The Firmware flasher will not touch your data partition, so it will not format or modify your data.

## Download
- Refer to the [releases](https://github.com/spike0en/dodge_firmware_flasher/releases) section.

## Credits
- Nixsuki for the initial version of the Oneplus Flashable Firmwares.
- [WishmasterFlo](https://github.com/Wishmasterflo) for the [Oneplus Firmware Flasher](https://github.com/Wishmasterflo/Firmware_flasher).

