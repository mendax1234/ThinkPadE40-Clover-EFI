**English** | [中文](README_CN.md)

<div align="center">
<img src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg.pconline.com.cn%2Fimages%2Fproduct%2F4716%2F471675%2FE40_1.jpg&refer=http%3A%2F%2Fimg.pconline.com.cn&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1614598580&t=aff4e5811033d603c6e85bdb90faf155" width="350px">
</div>

# ThinkpadE40-Clover-EFI

## Intro
 **This includes an EFI(Opencore) which works partly perfect on Thinkpad-E40.**
 
## Download
**You can click this button or turn to the "Releases" page yourself and download the latest version [![Download from https://github.com/mendax1234/ThinkPadE40-Clover-EFI/releases](https://img.shields.io/github/downloads/mendax1234/ThinkPadE40-Clover-EFI/total)](https://github.com/mendax1234/ThinkPadE40-Clover-EFI/releases)**

## Disclaimer

Your warranty is now void. Please do some research if you have any concerns before replacing your EFI with mine. I am not responsible for any loss, including but not limited to Kernel Panic, device fail to boot or can not function normally, storage damage or data loss, atomic bombing, World War III, Google and Apple both go into liquidation, and so on.

## Method of use

- Download from [PanBaidu](https://pan.baidu.com/s/1ugbLwDw-sDnWv0UZzgLxXg) 
 , the Extract code is ***nghf*** 
- After the installation disk is made without adding any EFI file into the installation interface (here should have CLOVER5106 iso, first under the Windows with EASYBCD2.3 add startup guide, here I am with CLOVER4871. The first iso add lead after talking about the black GuoXiaoBing macOS 10.15.4 DMG burn to the U disk, which could be directly into CLOVER5106 starts interface, don't need UEFI, just up every time want to plug in usb flash drive
- Enter the system to normal operation after installation, but notice don't turn it off after installation, enter the terminal, input 
> copytempdata

then it will let you choose is the partition, choose you to that one partition, then reboot to restart. If you can't restart, forced shutdown.
- The next step is to put the good EFI directly into the system disk root directory, and then enter the Clover guide interface, select system disk and press space to select -V and -S
- Enter with single user mode, 
  Enter the following command:
 > hfsupdatecache

- Waiting for it automatically completed, then the computer will automatically restart.
- Once again into the system tray, if you can choose "area and country", set up the user name, complete registration! ! !


## ThinkPad E40 Hackintosh

macOS Catalina/Mojave/High Sierra/Sierra/EI Capitan/Yosemite/Mavericks on ThinkPad E40 (Hackintosh).

### Tested on:
**Mavericks**
- 10.9.1
- 10.9.2
- 10.9.3
- 10.9.4
- 10.9.5
- 10.9.6

**Yosemite**
- 10.10.1
- 10.10.2
- 10.10.3
- 10.10.4
- 10.10.5
- 10.10.6

**EI Capitan**
- 10.11.1
- 10.11.2
- 10.11.3
- 10.11.4
- 10.11.5
- 10.11.6

**Sierra**
- 10.12.1
- 10.12.2
- 10.12.3
- 10.12.4
- 10.12.5
- 10.12.6

**High Sierra**
- 10.13.1
- 10.13.2
- 10.13.3
- 10.13.4
- 10.13.5
- 10.13.6

**Mojave**
- 10.14.1
- 10.14.2
- 10.14.3
- 10.14.4
- 10.14.5
- 10.14.6

**Catalina**
- 10.15.2
- 10.15.3
- 10.15.4
- 10.15.5
- 10.15.6
- 10.15.7

## Devices

| Specifications | Details |
|:---|:---|
| Computer Model | ThinkPad E40 |
| CPU | Intel Core i3 M 370 @2.40GHz .Dual cores |
| Mainboard | Lenevo 0579AS9 (HM55) |
| Memory | DDR3 1333 Mhz. 4 GB |
| NVMe SSD | Kingston (256G/SSD) |
| Integrated Graphics | AMD Mobility RadeonHD 545v |
| Ethernet |  Realtek 8111 |
| Display | LG LGD02E9 |
| Sound Card | Realtek ALC269 (Use VoodooHDA to dirve perfectly.) |


## What is working

#### CPU

Functioning normally.Frequency conversion is normal.

#### Battery

The power display is functioning normally.

#### USB

USB Ports Patching with HackinTool.

#### Ethernet

Functioning normally.

#### Display

Functioning normally.

#### Audio

Driven by VoodooHDA. Everything is working normally.

#### Keyboard

Functioning normally except the <kbd>Insert</kbd> , which is not presented on Magic Keyboard.And <kbd>Alt</kbd> represents Window's <kbd>Ctrl</kbd>.

#### SSD

SATA is functioning normally.

#### Trackpad & Trackpoint

Functioning normally. Trackpoint and UltraNavs are working properly as well.


## What is not working

- Airdrops and Handoff Fail to work properly.

## Tips

### Hibernation

Hibernation is supported.

## Further more help
  - For further learning please turn to [pcbeta](http://bbs.pcbeta.com/viewthread-1851317-1-1.html)

## Questions and Issues
  - If you have any questions,just push your issues on the Github , maybe l will help you!
  - Or If you have other questions or feedback, feel free to [![Gitter](https://badges.gitter.im/ThinkpadX390-Opencore-EFI/Hackintosh-ThinkPad.svg)](https://gitter.im/ThinkpadX390-Opencore-EFI/Hackintosh-ThinkPad?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
  - We only accept bug reports in GitHub Issues, before opening an issue, you're recommended to reconfirm it with us on [Gitter](https://gitter.im/ThinkpadX390-Opencore-EFI/Hackintosh-ThinkPad?utm_source=share-link&utm_medium=link&utm_campaign=share-link).
  
## Credits
  - [Apple](https://www.apple.com) for [macOS](https://www.apple.com/macos)
  - [@Acidanthera](https://github.com/acidanthera) for basic kexts.
  - [@SukkaW](https://github.com/SukkaW) for [Text and Templates](https://github.com/SukkaW/ThinkPad-E480-Hackintosh)
