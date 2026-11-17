# File Recovery Portal support

File Recovery Portal is published by MindtheApp. It is a front end for Microsoft's Windows
File Recovery tool, with a read-only preview of deleted files.

## Contact

Email: [mindthaapp@gmail.com](mailto:mindthaapp@gmail.com)

We usually reply within two working days. To help us answer quickly, please include:

- the app version (Settings > Apps > Installed apps > File Recovery Portal > Advanced options)
  and your Windows version;
- the type of drive you are recovering from (internal SSD or hard drive, USB stick, SD card)
  and its file system (NTFS, FAT32 or exFAT), if you know it;
- what you did and what happened, with the exact text of any error message.

Please do not send us your recovered files or drive images.

## Before you start a recovery

- **Stop using the drive.** Every new file written to the drive can overwrite deleted data.
- **Recover to a different drive.** The app requires the destination to be on a different
  drive from the one you are recovering from.
- **Administrator rights are needed.** Windows File Recovery and raw drive reads need
  administrator rights, so Windows shows a permission (UAC) prompt when you start a scan,
  preview, recovery, image or mount. If you decline it, nothing happens.
- The app opens the drive you recover from read-only. It never formats, repairs or writes to it.

## Common questions

**Why can't the app find my file?**
Recovery depends on the file system, the file type and how much the drive has been used
since the file was deleted. On SSDs, TRIM can erase deleted data soon after deletion, and no
tool can bring that data back.

**Does it work in Windows S mode?**
No. S mode does not allow the administrator rights the recovery needs.

**Which drives does the preview support?**
The deleted-file preview supports NTFS drives. Recovery itself also works on FAT and exFAT
drives through Windows File Recovery.

## Privacy

See the [File Recovery Portal privacy policy](privacy.html).
