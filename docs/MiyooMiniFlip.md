# MiyooMiniFlip

1. Take out sd card and format to FAT32 (NOT EXFAT) via rufus win
   - Device; E:
   - Boot Selection; non bootable
   - Partition Scheme; MBR
   - **File System; Large FAT32**
     - Check device for bad blocks; (optional)
3. Install [Onion OS](https://github.com/OnionUI/Onion/releases/tag/latest) (4.4.0) , extract files onto flashed sd card (deleting original OnionOS/ folder) and eject
4. Fresh setup Onion OS (go through complete cycle) , Shut down and take out sd card
5. Move any saved ROMS/ to SD card Roms/
6. Copy over Emu/ from (stock)/ without other emulator types (except GBA, GBC, GB) and eject
7. Go through entire Onion Setup
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
       - Wifi; On (connect, important later)
       - Menu Sound; 10/20
       - Sleep Timer; 15min
8. Power Flush, force recheck for updates sync etc.
9. Mark Favorites & Play
---

Issues & Fixes
- Game Console not popping up, copy paste Emu/ + corresponding folder w/ contents
- Saving state's is fragile (stores all data) but storing in game save (.srm) is more reliable and stable, contents are stored at `E(SDcard):\Saves\CurrentProfile\saves\gpSP\`

[Setup Video](https://www.youtube.com/watch?v=Udv7FKxg9SQ&t=1244s)
[OnionOS]()
