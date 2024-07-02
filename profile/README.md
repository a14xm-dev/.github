# Project A146P: The Unofficial Upgrade
![Banner](https://i.mediatek.com/hubfs/D700/banner.svg)

**About Me:**

Hello! I'm Martin, a medical student with a passion for embedded systems and Android development. While my primary focus is on studying medicine, I explore the world of tech in my free time. This organization is where I experiment with custom ROMs, kernels, and other software projects.

**Current Projects:**

* **Samsung Galaxy A14 5G (A146p) Development:**
    * Aiming to build a custom ROM for this entry-level device, enhancing its capabilities and user experience.
    * Working on the initial device tree and kernel setup
 ![bannerA14](https://hitecmobile.com.sg/media/wysiwyg/A14_banner1.jpeg)
* **Legacy Device Support (Galaxy Tab A 10.1):**
    * Continuing to explore ways to improve older devices through custom ROMs.
    * Facing challenges with limited RAM and outdated kernels.

**Why Android Development & Embedded Systems?**

I'm fascinated by the intersection of hardware and software. Embedded systems are everywhere, from medical devices to smartphones, and I love the idea of building software that directly interacts with these systems. Android development in particular, lets me optimize the devices I use daily.

**Managing Studies & Development:**

Medical school is demanding, so my development is sporadic. I work on projects when I have free time, which may be infrequent. I hope to contribute to the community whenever I can, even if it's just small steps.

**You Can Contribute (If Interested):**

* **Testing:** When builds are available, feedback is encouraged. Try them out, report bugs, and let me know what works well and what needs improvement. I'm open to new ideas and suggestions. If you have thoughts on features or optimizations, please share them!

**Disclaimer:**

These projects are experimental. I'm still learning and improving, so expect some bumps along the road. Always back up your data before trying any custom software. 

# Flashing ROMs and Custom Recovery on Samsung Devices

   - Procedure will generally apply across most Samsung devices 

Prerequisites:
- 
- [Odin v3.13.1](https://build.nethunter.com/samsung-tools/)
  - There are plenty of ¨official¨ Odin links. Odin is proprietary software which has never been officially released by Samsung
  - XDA threads or Nethunter repository are the most reputable sources for finding it. I choose the latter
- Fresh install or flash of the [latest available firmware](https://samfw.com/firmware/SM-A146P/)
 
ROM Downloads: 
- 
- Work in progress. 

General Installation Instructions (TWRP): 

From stock OEM firmware:
-
- [Unlock bootloader](https://www.ifixit.com/Guide/How+to+unlock+the+bootloader+of+an+Android+Phone/152629)
- Power the device off
- Hold Vol Up & Vol Down buttons while plugging the USB-C from PC into device to enter Download mode
 
- Flash the custom ROM tarball (.tar.md5 file) to the AP slot with Odin
- If TWRP launches, factory reset with Wipe->Format Data and reboot to system. (Not necessary for incremental upgrades.)

From existing TWRP install:
-
- Hold Power & Vol Up during restart to enter TWRP recovery
- Tap Install, Install Image, select your update (.img file), OR Install via [ZIP archive]. 
- Factory reset with Wipe -> Format Data. (Not necessary for incremental upgrades.)
- Reboot to system

**Thank you for visiting!.** 🩺📱💻
---

