![Mist](https://github.com/Project-Mist-OS/manifest/blob/15-wip/assets/Banner.png)
# <b> <i> MistOS | Built with </i>💖

# This is Project-Mist-OS [Mist OS]

### Initialize local repository

```
repo init -u https://github.com/Mist-OS-Staging/manifest -b 16 --git-lfs
```

### Sync up 

```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
# Maintainer flag 
```
MISTOS_MAINTAINER="XXX"
```

# GMS flag
```
WITH_GMS := true/false
```

# Optional GMS / Default is Full GMS
```
TARGET_USES_MINI_GAPPS := true/false
TARGET_USES_PICO_GAPPS := true/false
```
# Blur 
```
TARGET_ENABLE_BLUR := true/false
```
# Build

```
. build/envsetup.sh
```
---

```
mistify <devicecodename> user | userdebug
```
---
```
mist b 
```

## Credits
 * [**risingOS**](https://github.com/RisingTechOSS)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**Evolution X**](https://github.com/Evolution-X)
 * [**The Parasite Project**](https://github.com/TheParasiteProject)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**SuperiorOS**](https://github.com/superioros)
 * [**Project Awaken**](https://github.com/Project-Awaken)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**Yet another AOSP project**](https://github.com/Yaap)
 * [**Pixel OS**](https://github.com/pixelos-aosp)
 * [**ProjectBlaze**](https://github.com/ProjectBlaze)
 * [**Superior Extended**](https://github.com/SuperiorExtended)
 * [**And Others**]
