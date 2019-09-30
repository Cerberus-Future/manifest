# Cerberus OS #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Cerberus-Future/manifest -b 10

# Sync
repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

## Credits
-  [Syberia-Project] (https://github.com/syberia-project)
-  [PixelExperience](https://github.com/PixelExperience)
-  [LineageOS](http://GitHub.com/LineageOS)
