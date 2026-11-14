# MiyooMiniFlip

1. Take out sd card and format to FAT32 (NOT EXFAT) via rufus win
   - Device; E:
   - Boot Selection; non bootable
   - Partition Scheme; MBR
   - **File System; Large FAT32**
     - Check device for bad blocks; (optional)
3. Install [Onion OS](https://github.com/OnionUI/Onion/releases/tag/latest) (4.4.0) , extract files onto flashed sd card and eject
4. Fresh setup Onion OS (go through complete cycle) , Shut down and take out sd card
5. move roms to sd card
6. go through entire Onion Setup
   - Apps
       - Themes; 3DS mini
       - Tweaks;
         - System;
           - Startup;
             - Auto-resume last; Off
           - Date&Time;
             - Set automatically; On
             - Wait for sync on startup; On
             - Enable Wifi; On
             - Select time zone; UTC-5
           - Low Battery; <20%
   - Settings
       - Wifi; On (connect)
       - Menu Sound; 10/20
       - Sleep Timer; 15min

---

Issues & Fixes
- Game Console not popping up, copy paste Emu/ + corresponding folder w/ contents

[Setup Video](https://www.youtube.com/watch?v=Udv7FKxg9SQ&t=1244s)
[OnionOS]()
