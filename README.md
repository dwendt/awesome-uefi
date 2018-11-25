# awesome-uefi

Security-focused collection of UEFI links I personally found useful.

- [Awesome UEFI](#awesome-uefi)
    - [Fundamentals](#fundamentals)
    - [Writeups](#writeups)
    - [Dumping](#dumping)
    - [Inspection](#inspection)
    - [Reversing](#reversing)

- - -
## Fundamentals
* **[Chipsec](https://github.com/chipsec/chipsec)** - Framework and tooling for doing runtime analysis of a lot more than UEFI.

## Writeups
* [Jethro Beekman's Lenovo HDD Password series](https://jbeekman.nl/blog/2015/03/reverse-engineering-uefi-firmware/) - Beginner-accessible walkthrough on reversing a UEFI-implemented disk encryption mechanism.
* [Copernicus - 2015](https://www.blackhat.com/docs/us-13/US-13-Butterworth-BIOS-Security-Code.zip)[tweet](https://twitter.com/XenoKovah/status/647047425417474048) - MITRE's project for monitoring UEFI on Windows. Closed-source.

## Dumping

## Inspection
* [UEFITool, UEFIExtract, UEFIFind](https://github.com/LongSoft/UEFITool) - Cross-plat tooling for inspecting firmware images.

## Reversing
* ida scripts here

## Modding / Flashing
* MMTOOL - American Megatrends' proprietary BIOS image modification tool (aptio4).
* [UBU](https://firmwaresecurity.com/2016/08/28/uefi-bios-updater-ubu-updated/) - useful for replacing binaries in a UEFI BIOS image, wraps MMTOOL. should be obsoleted by uefitool I think, todo 
