### This repo is for my personal use only kindly do not bother me with question like why did you track your device tree in rom manifest, you will recieve no response ###

<p align="center">

<img src="https://github.com/litmusos/manifest/blob/thirteen/Litmus.png">

</p>

# Litmus OS #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/vertigo-trees/litmus_manifest -b thirteen

```

```bash

# Sync
repo sync -c -j$100 --force-sync --no-clone-bundle --no-tags

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
