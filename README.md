# Hackintosh-G14-GA401IV-
MacOS 14.7.5 success with the G14 2020 Model (I call it the *ROG Zephyrus i14*)<br>
Laptop Model: **[Link](https://rog.asus.com/laptops/rog-zephyrus/rog-zephyrus-g14-series/)**
# Important
This page will never be updated, since it was supposed to be a side project I am working on.<br>
Though I managed to get macOS on my laptop, I don't use it as much, so unless it stops working,<br> 
I won't be updating the page.
# Note 
Best if someone forks this page and makes it support newer macOS updates!<br>
**Not Working:**<br>
*iMessage*<br>
*Airdrop*<br>
# Required
- USB: (**Minimum 32GB**)
- Storage: (**Minimum 100GB**)
- macOS installer image: (Version **12** - **14.7.5 Only**)
- Explorer++: **[Link](https://explorerplusplus.com/)**
- Mini Partition Tool: **[Link](https://www.partitionwizard.com/)**
- UMAF: **[Link](https://github.com/DavidS95/Smokeless_UMAF/)**
- Rufus: **[Link](https://rufus.ie/en/)**
# Recommended
- Add a Restore Point on Windows
- Having OS management experience
- Having Linux management Experience
- Have an Apple Account
# Instructions
- **Update BIOS**
- Change your BIOS Using (UMAF):
  - *IGPU Configuration* to *UMA_SPECIFIED*
  - *UMA Frame buffer* - *1g* or *2g*
  - Enable *Above 4g decoding*
  - Disable *Fast boot*
  - Disable *Scecure boot*
- **Create a Flash installer on your USB**
  - Download a copy of macOS installer somewhere (Google it)
  - Then use Rufus
- **Using (Mini Tool)**
  - Partition Disk for macOS on your preferred storage
- **Using (Explorer++) - Run as Admin**
  - Replace the Boot and OC files in the USB (from the release)
-  Restart and Boot to the USB
- **Run "Reset NVRam"** 
- **Run "macOS installer"**
- If successful, it will boot to recovery mode
- **Using Disk Utility:**
  - Write on the disk you partitioned
  - Choose "APFS" as the format
- **Install macOS**
  - When you restart, go to "install macOS"
  - Should do this a few times
- BOOM macOS is now yours 🤯.
- Login setup: Move the boot files from USB to the BOOT partition.
- **Now you're done 😝.**

# Pictures 
![Boot Image](https://github.com/user-attachments/assets/a3bc7385-e4f5-43e3-af54-cc5d75e3c399)

![Running Image](https://github.com/user-attachments/assets/3f32d1c7-7267-4a61-8306-2aac579ecbb9)

