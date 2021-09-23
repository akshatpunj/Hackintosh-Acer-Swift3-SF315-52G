# Hackintosh-Acer-Swift3-SF315-52G
 Hackintosh Acer Swift3 SF315-52G (With Intel Wifi & BT)

Run macOS High Sierra(10.13), Mojave(10.14), Catalina(10.15), Big Sur(11.0) on an Acer Swift3 SF315 52G.
Most pieces are fully supported, and this setup can be used as your main machine. A few pieces are missing (and some will probably never be supported).

You can use the EFI folder to be to boot into a USB installer, or for regular booting.
** Hackintosh Acer-Swift3-SF315-52G
  - CPU : Intel Core i5-8250U (Kabylake-R)
  - Graphics : Intel UHD 620 (+ MX150)
  - RAM : SK Hynix HMA81GS6CJR8N-VK 8 GB DDR4 2666 MHz (2 slot, maximum upgrade 32GB)
  - SSD : Hynix 256GB M.2 SOLID STATE DRIVE 80MM L (HFS256G39TND-N210A) Read : Up to 530MB/s(128/256/512GB)\ Write : Up to 190MB/s(128GB)
  - Screen : 15.6-inch 1920 x 1080 glossy IPS
  - Ports : 2 x USB 3.0, HDMI (Full Size), USB 2.0, USB Type-C, 1xAudio jack
  - Wifi/Bluetooth : Intel AC-7265, (M.2 NGFF)
  - Audio : ALC256
  - SD Card Reader : Realtek USB2.0-CRW (ven id:0bda, dev id:0129)
  - Back-lit keyboard
  - Controller (Synaptic): VoodooI2CHID, VoodooI2C + PS2Controller
** What is working
  - Graphics: Intel UHD Graphics 620 (Disable MX150)
  - Audio: Speakers, headphones (Mic don't work)
  - Keyboard: Backlight is ACPI-managed so it works just fine too
  - Trackpad: Patch I2C + VoodooI2CHID,VoodooI2C makes it buttery-smooth, supports all the macOS gestures
  - USB: Full support
  - Webcam: PhotoBooth works fine
  - Sleep/Wake: works very well
  - Wifi/Bluetooth
  - HDMI
  - SD Card Reader

** What is not working
  - Mic: Doesn't Work
  - GPU: MX150 (No support at all)
  - Fingerprint

  ## Credits

- **Special Thanks** to [dortania](https://dortania.github.io/vanilla-laptop-guide) for the vanilla laptop guide.
- **Special Thanks** to [Acidanthera](https://github.com/acidanthera) for most of the Kexts.
- **Special Thanks** to [Linh Nguyen](https://github.com/linhnguyen-gt) for all the files and clear guidance (Do visit his repo for more insights).
- Thanks to [OpenCore Bootloader](https://https://github.com/acidanthera/OpenCorePkg).
- Thanks to [daliansky](https://github.com/daliansky) for [ACPI Hotpatch Samples for the OpenCore Bootloader](https://github.com/daliansky/OC-little).
- Thanks to [alexandred](https://github.com/alexandred) for [VoodooI2C](https://github.com/alexandred/VoodooI2C).
- Thanks to [hackintosh-stuff](https://github.com/hackintosh-stuff) for [ComboJack support for ALC255](https://github.com/hackintosh-stuff/ComboJack).
- Thanks to [corpnewt](https://github.com/corpnewt) for [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).
- Thanks to [VampFOX67](https://github.com/VampFOX67) for sharing bluetooth fix.
