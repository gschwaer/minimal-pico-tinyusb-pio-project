# Minimal Raspberry Pi Pico TinyUSB Project

## Setup

```shell
git clone --no-recurse-submodules https://github.com/gschwaer/minimal-pico-tinyusb-pio-project.git
cd minimal-pico-tinyusb-pio-project
git submodule update --init -- pico-sdk
git -C pico-sdk submodule update --init -- lib/tinyusb
```

## Build

```shell
cmake -B build
make -C build
```
