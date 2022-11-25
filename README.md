# Michi USB C Pro Micro RP2040

![michi-pro-micro](https://github.com/ci-bus/michi/blob/master/conjunto3d.jpeg)

## Compile QMK Firmware to Michi .uf2 file 

### Examples:
Using QMK CLI:
```
qmk flash -c -kb crkbd -km default -e CONVERT_TO=michi
```
Using make:
```
make crkbd:default CONVERT_TO=michi
```

## Flashing

1. Join **Boot** with **GND** pins or press reset button if you keyboard have this
2. Connect USB
3. Remove the bridge or release the reset botton
4. Wait for OS to detect Michi
5. Copy the .uf2 file to the USB drive
