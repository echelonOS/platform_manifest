echelonOS
========

To initialize your local repository, use this command:

	repo init -u https://github.com/echelonOS/platform_manifest.git -b pie
  
 Then to sync up:

```bash
repo sync -f --force-sync --no-tag --no-clone-bundle -j$(nproc --all) --optimized-fetch --prune
```

Finally to build:

```bash
. build/envsetup.sh
lunch echelon_codename-userdebug
mka echelon
```

## Support
Join Telegram Group: https://t.me/echelonsupport
