# Building/Running Firmware & Software

## Environment Setup

The IDE:

- install `VS Code`
- install `PlatformIO` extension

PlatformIO wasn't resolving the libraries correctly. Adding it to path resolved this for me.

- add `C:/Users/YOUR_USERNAME/.platformio/penv/Scripts/` to path

## Helpful Commands

```sh
# update dependencies
pio lib update
```