![Mist](https://github.com/Project-Mist-OS/manifest/blob/13.1/assets/Banner2.jpg)
# <b> <i> MistOS | Built with </i>💖

---------------

Getting Started
---------------

To get started with Android, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).
To set up your build environment and sync Mist, please follow this guide: [Link](https://raw.githubusercontent.com/nathanchance/android-tools/main/guides/building_aosp.txt)

**To initialize your local repository using the AOSP/CAF based Mist source, use a command like this:**

```bash
   repo init -u https://github.com/Project-Mist-OS/manifest -b 14
```
**Sync up with this command:**
```bash
   repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Building the source
---------------

The source at MistOS is well configured for building.

**Initiate the build with:**
```bash
   . build/envsetup.sh
```
**Prepare your device with:**
```bash 
   lunch mist_$device-user
```
**Then fire it off with:**
```bash
   mka bacon
```

Thanks section
---------------

Here's my thanks to people who made this possible:

* ABC
* AICP
* AOSiP
* AOSPA
* ArrowOS
* Bianca Project
* BootleggersROM
* CyanogenMod/LineageOS
* CherishOS
* CipherOS
* DirtyUnicorns
* DerpFest-AOSP
* NitrogenOS
* Nusantara-ROM
* OmniROM
* PixelExperience
* POSP
* Project Fluid
* Project Kaleidoscope
* RiceDroid
* ShapeShiftOS
* Syberia Project
* tequilaOS
* YAAP
 And Many More

Using our assets
---------------

**Code**

Our codebase is licensed under Apache License, Version 2.0 unless otherwise specified. Apache License 2.0 allows a variety of actions on the content as long as licensing and copyright notices are retained and included with the code and your changes to the codebase are stated.

You can read the full license text at http://www.apache.org/licenses/LICENSE-2.0

**Images & other assets**

Unless otherwise specified, all out assets, including but not limited to images, are licensed under Creative Commons Attribution-NonCommercial 4.0 International, or CC BY-NC 4.0 for short. This means that you are allowed to modify the aforementioned assets in any way you want and you are free to share the originals and/or the modified work. However, you are not allowed to use the assets for commercial purposes and you must provide attribution at all times which means you have to include a short note about the license used (CC BY-NC 4.0), the original author/authors (DerpFest) and inform about any changes that have been made. A link to the website ( derpfest.org ) should usually be included as well.

You can reach the full legal text at http://creativecommons.org/licenses/by-nc/4.0/
