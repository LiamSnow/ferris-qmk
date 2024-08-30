# ferris-qmk
My QMK config/keymap for the Ferris split ergo keyboard

## Compile
Make sure you have the QMK toolbox installed (`paru -S qmk`).

```bash
qmk compile ferris_0_1_liamsnow.json
```

## Flash
```bash
qmk flash ~/qmk_firmware/.build/ferris_0_1_ferris_0_1_liamsnow.hex
```
