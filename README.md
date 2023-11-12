# mi-unlock for Android
A program that can be used to unlock the bootloader for Xiaomi devices

## Official tool source
[RohitVerma882](https://github.com/RohitVerma882/termux-miunlock.git)

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
