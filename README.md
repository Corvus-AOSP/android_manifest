### Corvus ROM ###

![CorvusROM](https://raw.githubusercontent.com/Astile97/extras/master/corvus/cover.PNG)
<p align="center">

[![Sourceforge](https://img.shields.io/sourceforge/dm/corvus-os?color=1d91f0&label=RavenLair%20downloads&style=for-the-badge&labelColor=121217&logo=github)](https://corvus-rom.github.io/)
</p>

# Initialize Local Repository #
```bash
repo init -u https://github.com/Corvus-R/android_manifest.git -b 11
```

# Or Initialize Shallow Clone #
```bash
repo init --depth=1 -u https://github.com/Corvus-R/android_manifest.git -b 11
```

# Syncing Repository # 
```bash
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```

# Building Environment #
```bash   
# Set up environment
. build/envsetup.sh

# Choose a target
lunch corvus_device-userdebug

# Build the ROM
make corvus
```
# Corvus Forums Template
[![Corvus_Forums-Template](https://raw.githubusercontent.com/SahilKhatkar11/Corvus_forums-logo/main/Corvus_Forums_Logo.png)](https://raw.githubusercontent.com/Corvus-ROM/android_manifest/11/corvus_forums)

# Maintainership form
[![Form](https://raw.githubusercontent.com/rashedsahaji/RandomStuff/master/Submission_button.png)](https://docs.google.com/forms/d/e/1FAIpQLSeOEzQXfNnPehPQRXxmt3L5FYc5neOhEE3m6ZW_xbIuuQ-dCg/viewform?usp=sf_link)

# Telegram Support 
[![Telegram](https://raw.githubusercontent.com/rashedsahaji/RandomStuff/master/Telegram_button.png)](https://t.me/CorvusCommunityOfficial)

 Credits:
 =======

 * [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**HavocOS**](https://github.com/Havoc-OS)
 * [**LineageOS**](https://github.com/LineageOS/)
