# Lenovo_miix720_hackintosh_sequoia
Opencore 1.0.7 EFI for Lenovo miix720 on macOS sequoia 15.7.3

# Mechine Spec
note: I have several modification made on my mechine, this shouldn't cause any issue on your system but your mileage may vary.
- CPU: Core I5-7200U@2.71 Ghz
- GPU: Intel HD 620 graphics
- DDR4 8G RAM+ 1T nvme SSD (MAP1202 controller, originally uses PM951)
- Network card: Intel AX210(this mechine comes with AC8265 which should also work using these kexts, but was not tested)

# V1 Current problems
- bluetooth have trouble connecting certain Keyboard and mouse, Probably related to AX210 Kexts issue. Bluetooth headphones and phones connects just fine. Still looking into it.
- reoccuring shutdown issues, causes device reboots on shutdown, for the time being it works.
- rear camera can't be recognized by Macos, selfie cam works.
- SD card reader doesn't work(probably related to lack of SSDT)
- pogo keyboard needed to be reconnected once after boot, then it works fine.
- WIFI may display WPA warnings but was working in WPA2, don't worry.
- WIFI setting in setting app might encounter bugs, use control center.

# credit
- [opencore project](https://github.com/acidanthera/OpenCorePkg)
- [previous MIIX720 EFI Projects](https://github.com/Sunbertrs/Lenovo_Miix720_Hackintosh)
- [OpCore-Simplify Project](https://github.com/lzhoang2801/OpCore-Simplify)
