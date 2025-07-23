---
{"dg-publish":true,"permalink":"/projects/system-reformat-checklist/","tags":["Projects","Tech"],"created":"2025-07-21","updated":"2025-07-22T23:07:35.002-04:00"}
---

# About This Project
Reinstalling windows on your main machine is a bitch; No two ways about it. It's even worse when you forget something have play detective and figure out where it went wrong. Hence, this list was born to maintain my personal sanity.

---
# Preparation

1. Get your [[Tech/OS Product Key\|OS Product Key]]
2. Download the most updated drivers for your hardware
3. Sync your browser account
4. Backup files, documents, etc
	1. You can use [Game Save Manager](https://www.gamesave-manager.com/) to back up your game save data

> [!warning]
> Make sure to double check your "user data" folder for anything you need to backup. For windows this would be `C:/Users/{USERNAME}?AppData/` and copy and important files from the `Local` or `Roaming` folders.

---
# Make a Bootable Drive

You'll need to make a bootable drive containing the [[Tech/OS Image\|OS Image]] you're installing on the system. 

---
# Installing From our Bootable Drive
1. Enter your computer's bios mode
2. Change the `boot order` and set the freshly made [[Projects/System Reformat Checklist#Make a Bootable Drive\|Bootable Drive]] to come first
3. Save your changes and restart the system
4. You should now be greeted with the GUI for installing your desired OS

---
# Optimizing Settings
Depending on the OS you installed there are some steps you should take on the first time boot of the operating system.
- [[Tech/First Boot Config - Windows\|First Boot Config - Windows]]
- [[Tech/First Boot Config - Batocera\|First Boot Config - Batocera]]

---
# Installing Programs
Finally, you can use your desired [[Tech/My Install Package\|Install Package]] and configure the programs as desired. Here are a few tips to remember:
- After logging into a service/software make sure to disable boot on startup if not needed

---