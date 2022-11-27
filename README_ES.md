# Michi USB C Pro Micro RP2040

![michi-pro-micro](https://github.com/ci-bus/michi/blob/master/pinout.jpeg)

## Compilando [QMK Firmware](https://docs.qmk.fm/) archivo .uf2 para Michi

### Ejemplos:
Usando QMK CLI:
```
qmk flash -c -kb crkbd -km default -e CONVERT_TO=michi
```
Usando make:
```
make crkbd:default CONVERT_TO=michi
```

## Flasheando

1. Haz un puente entre los pines **Boot** y **GND** o mantén presionado el botón reset si tu teclado lo tiene
2. Conecta el USB
3. Elimina el puente o suelta el botón reset
4. Espera a que el sistema operativo detecte a Michi
5. Copia el archivo .uf2 dentro de la memoria USB

## Notas

El código de Michi aún no se encuentra en el repositorio oficial de QMK firmware, por ahora tu puedes usar la rama forked.

[QMK firmware Michi](https://github.com/ci-bus/qmk_firmware/tree/promicro-michi-rp2040)


## Diseñador

Miguelio - [website](https://miguelio.com/) - [instagram](https://www.instagram.com/migueliokeyboards/)
  
## Colaborador

Tecleate - [website](https://tecleate.com/) - [instagram](https://www.instagram.com/tecleate/)
