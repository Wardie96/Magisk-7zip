# Magisk-7zip

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This Magisk module injects the standalone static `7zz` binary into `/system/bin`, providing a powerful command-line archiving utility for Android.

## Features
- **Standalone Binary:** Includes the official `7zz` static binary.
- **System-wide Access:** Injects into `/system/bin` for easy access from any terminal.
- **Wide Compatibility:** Tested on various Android versions and root solutions (Magisk, APatch).

## Installation
1. Download the latest release zip.
2. Open the Magisk app (or your preferred module manager).
3. Go to the "Modules" tab.
4. Tap "Install from storage" and select the zip file.
5. Reboot your device.

## Usage
Open a terminal emulator (like Termux) and run:
```bash
7zz --help
```

## Compatibility
- Tested on Pixel 6 - Android 16 (Magisk)
- Tested on OnePlus 8T - OOS 11 (APatch)

## Credits
- [7-Zip 26.00](https://www.7-zip.org/) by Igor Pavlov.
- Magisk by topjohnwu.

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Third Party Licenses
The `7zz` binary included in this module is part of the 7-Zip project by Igor Pavlov and is licensed under the **GNU Lesser General Public License (LGPL) v2.1 or later**. 

You can find the source code for 7-Zip at [7-zip.org](https://www.7-zip.org/download.html). A copy of the LGPL v2.1 is included in the [THIRD_PARTY_LICENSES/LGPL-2.1.txt](THIRD_PARTY_LICENSES/LGPL-2.1.txt) file.
