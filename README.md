### Corvus ROM ###

![CorvusROM](https://raw.githubusercontent.com/Corvus-R/android_manifest/12-test/corvus_banner.png)
<p align="center">

[![Sourceforge](https://img.shields.io/sourceforge/dm/corvus-os?color=1d91f0&label=RavenLair%20downloads&style=for-the-badge&labelColor=121217&logo=github)](https://corvus-rom.github.io/)
</p>

# Initialize Local Repository #
```bash
repo init -u https://github.com/Corvus-R/android_manifest.git -b 12-test
```

# Or Initialize Shallow Clone #
```bash
repo init --depth=1 -u https://github.com/Corvus-R/android_manifest.git -b 12-test
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

# Maintainership form
[![Form](https://raw.githubusercontent.com/rashedsahaji/RandomStuff/master/Submission_button.png)](https://docs.google.com/forms/d/e/1FAIpQLSeOEzQXfNnPehPQRXxmt3L5FYc5neOhEE3m6ZW_xbIuuQ-dCg/viewform?usp=sf_link)

# Telegram Support 
[![Telegram](https://raw.githubusercontent.com/rashedsahaji/RandomStuff/master/Telegram_button.png)](https://t.me/CorvusCommunityOfficial)

 Credits:
 =======
 Kudos to every Amazing rom out there who've relentlessly contributed to the Open Source beauty of Android!
