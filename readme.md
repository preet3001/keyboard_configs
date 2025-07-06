stow qmk to your qmk_firmware directory

```bash
stow  qmk
```


to complile a keymap, run:

```bash
qmk compile -kb <keyboard> -km <keymap>
``` 
to flash a keyboard, run:

```bash
qmk flash -kb <keyboard> -km <keymap>
```


for example, to compile the keymap for a corne keyboard:

```bash
qmk compile -kb crkbd -km hm_keymap
```
to flash the corne keyboard:

```bash
qmk flash -kb crkbd -km hm_keymap
```
