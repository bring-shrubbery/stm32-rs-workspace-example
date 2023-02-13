# Rust STM32 test

## Add toolchain

```sh
# Add new toolchain
rustup target add thumbxxx-xxxx-xxxx
```

## Building

```bash
# Build debug version
cargo build

# Build release version
cargo build --release
```

## Flashing

```sh
# Install flashing utility
cargo install cargo-flash

# flash binary to the chip using STLink v2
cargo flash --chip <stm32xxxxxx> --release
```

## Tooling links

- You can find which target you need to use in [cortex_m_quickstart](https://docs.rust-embedded.org/cortex-m-quickstart/cortex_m_quickstart/).
