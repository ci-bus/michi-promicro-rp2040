# Michi USB C Pro Micro RP2040

![michi-pro-micro](https://github.com/ci-bus/michi/blob/master/conjunto3d.jpeg)

## Compile QMK Firmware to Michi .uf2 file 

### Examples:
Using QMK CLI:
```
qmk flash -c -kb keebio/levinson/rev3 -km default -e CONVERT_TO=promicro_rp2040
```
Using make:
```
make keebio/levinson/rev3:default CONVERT_TO=promicro_rp2040
```
