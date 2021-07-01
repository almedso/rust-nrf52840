# nRF52840 Stick Application

## Stick Capabilities

- USB connection
- BT connection
- Single button
- Single led

# Development Notes

- Pure rust project
- startup guided by:
  https://nitschinger.at/Getting-Started-with-the-nRF52840-in-Rust/
- uses: probe-run, defmt

## Environment

```
# Get the toolchain in place
rustup target add thumbv7em-none-eabihf

# Install embedded flash and access tool
cargo install probe-run
```
