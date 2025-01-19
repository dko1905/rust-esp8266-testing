# Rust on ESP8266 (v2025.0.0)

Project for building for ESP8266 chip.

## Nix

## Manual Installation


Install older version of `esp` Rust compiler for compatibility with older dependencies.

```sh
espup install --name esp-1.75.0.0 --toolchain-version 1.75.0.0
# To uninstall
#espup uninstall -n esp-1.75.0.0
```

Build Rust std (aka core crate):

```sh
cargo build -Zbuild-std --target xtensa-esp8266-none-elf
```
