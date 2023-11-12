# mi-unlock Tool for Xiaomi Devices
Unlock Xiaomi bootloader using a secondary phone via OTG.

### Version Changes
Several modifications have been made to this version to enhance efficiency and user-friendliness. Notable changes include:

- Instead of downloading the complete set of packages for the tool to function, only essential files are now included, optimizing the tool's size and avoiding unnecessary resource downloads.

- The tool's usability has been simplified. Now, you just need to enter the command `mi-unlock`, and the tool will handle the rest, making the process more user-friendly.

Official Tool Source [RohitVerma882](https://github.com/RohitVerma882/termux-miunlock.git)

## Instructions
1) download [mi-unlock](https://github.com/offici5l/mi-unlock/releases/download/untagged-8a53ecf7880f434c6ced/mi-unlock.zip) and Unzip mi-unlock.zip

2) install account.apk / termux-app.apk / termux-api.apk

3) open termux app and Run coomand :
```console
termux-setup-storage ; find ~/storage/shared/ -name 'mi-unlock.tar.xz' -exec tar -kxf {} -C $PREFIX \; 2>/dev/null ; chmod +x $PREFIX/bin/mi-unlock ; mi-unlock
```

4) Use command :
```console
mi-unlock
```