# AURIX GCC Toolchain Mirror

Infineon officially provides the AURIX TriCore GCC toolchain at:
https://softwaretools.infineon.com/assets/com.ifx.tb.tool.aurixgcc

However, the download requires manual interaction and does not support
direct URL fetching (wget/curl), making it unusable for CI pipelines.

This repository mirrors the official Infineon AURIX GCC toolchain binaries
under GitHub Releases to enable automated downloads for Zephyr RTOS CI builds.

## Version

- **GCC 11.3** (March 2026) - Official Infineon release

## Usage

```
wget https://github.com/Linumiz/aurix-gcc-toolchain/releases/download/v11.3.0/aurixgcc_03-2026_Linux_x86-x64.zip
```

## Disclaimer

All toolchain binaries are property of Infineon Technologies AG.
This mirror exists solely for CI automation purposes.
For official downloads and license terms, refer to Infineon's site above.
