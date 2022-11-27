# Michi USB C Pro Micro RP2040

![michi-pro-micro](https://github.com/ci-bus/michi/blob/master/pinout.jpeg)

## Compile [QMK Firmware](https://docs.qmk.fm/) to Michi .uf2 file 

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

## Notes

The code not yet deployed in the official QMK firmware repository, for now you can use this forked and configured code.

[QMK firmware Michi](https://github.com/ci-bus/qmk_firmware/tree/promicro-michi-rp2040)


## Designer

Miguelio - [website](https://miguelio.com/) - [instagram](https://www.instagram.com/migueliokeyboards/)
  
## Collaborator

Tecleate - [website](https://tecleate.com/) - [instagram](https://www.instagram.com/tecleate/)
