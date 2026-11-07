# PixelOS (seventeen) for POCO F5 / Redmi Note 12 Turbo (marble)

Android 17, PixelOS `seventeen`, kernel 6.6 (based on cupid-development `lineage-24.0-6.6`).

```bash
repo init -u https://github.com/PixelOS-AOSP/android_manifest.git -b seventeen --git-lfs
git clone https://github.com/tgiraud2007/local_manifests -b seventeen .repo/local_manifests
repo sync -c -j8 --force-sync --no-tags
source build/envsetup.sh
lunch custom_marble-cp2a-userdebug
m pixelos
```

## Credits
- [cupid-development](https://github.com/cupid-development) — sm8450 device trees and kernel 6.6
- [LineageOS](https://github.com/LineageOS) and [PixelOS](https://github.com/PixelOS-AOSP)
