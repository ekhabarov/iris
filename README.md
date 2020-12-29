# Iris keyboard config

## Install qmk (Arch linux)
```shell
% pacman -S qmk
```

## Intall config
```shell
% git clone git@github.com:ekhabarov/iris.git
% mkdir ~/qmk_firmware/keyboards/keebio/iris/keymaps/ekhabarov
% ln -s ~/iris/* ~/qmk_firmware/keyboards/keebio/iris/keymaps/ekhabarov
```

## Configure QMK
```shell
% qmk config user.keymap=ekhabarov
% qmk config user.keyboard=keebio/iris/rev4
```

## Flash
```shell
% qmk flash
```



