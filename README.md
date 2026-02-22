# Differences from the original template:

- Remove risc-V support
- Add 4mb flash option
- better defmt support
- vsc settings and debug config
- Minor changes
- add probe-rs option on config.toml

# Pico 2 Template
A Rust project template for Raspberry Pi Pico 2 (RP2350) development.

## Usage

Generate a new project:

```sh
cargo generate --git https://github.com/ItsJupiter21/pico2-template.git
```

## Options

- HAL: Choose between Embassy (async) or rp-hal
- defmt logging: Optional debugging support
