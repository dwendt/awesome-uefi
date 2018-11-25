# awesome-uefi

Security-focused collection of UEFI links I personally found useful. [awesome-firmware-security](https://github.com/PreOS-Security/awesome-firmware-security) is a more general collection and may be more useful to you.

- [Awesome UEFI](#awesome-uefi)
    - [Fundamentals](#fundamentals)
    - [Writeups](#writeups)
    - [Dumping](#dumping)
    - [Inspection](#inspection)
    - [Reversing](#reversing)

- - -
### Fundamentals
* **[Chipsec](https://github.com/chipsec/chipsec)** - Framework and tooling for doing runtime analysis of a lot more than UEFI.

### Writeups
* [Jethro Beekman's Lenovo HDD Password series](https://jbeekman.nl/blog/2015/03/reverse-engineering-uefi-firmware/) - Beginner-accessible walkthrough on reversing a UEFI-implemented disk encryption mechanism.
* [Copernicus - 2015](https://www.blackhat.com/docs/us-13/US-13-Butterworth-BIOS-Security-Code.zip)[tweet](https://twitter.com/XenoKovah/status/647047425417474048) - MITRE's project for monitoring UEFI on Windows. Closed-source.

### Dumping
* [via Chipsec on Windows](https://github.com/chipsec/chipsec/issues/378) - asdf link the windows setup here too
* [via Chipsec on Linux]() - chipsec_util.py spi dump rom.bin
* [via flashrom on linux]()

### Inspection
* [UEFITool, UEFIExtract, UEFIFind](https://github.com/LongSoft/UEFITool) - Cross-plat tooling for inspecting firmware images.

### Reversing
* ida scripts here

### Modding / Flashing
* [uefi-firmware-parser](https://github.com/theopolis/uefi-firmware-parser) - Python library, parses firmware images.
* MMTOOL - American Megatrends' proprietary BIOS image modification tool (aptio4).
* [UBU](https://firmwaresecurity.com/2016/08/28/uefi-bios-updater-ubu-updated/) - useful for replacing binaries in a UEFI BIOS image, wraps MMTOOL. should be obsoleted by uefitool I think, todo 
