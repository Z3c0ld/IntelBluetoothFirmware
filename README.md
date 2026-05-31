# IntelBluetoothFirmware

![CI](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/workflows/CI/badge.svg)

- **English**
- [简体中文](/.github/README-zh_Hans.md)

## Intro

IntelBluetoothFirmware is a Kernel Extension that uploads Intel Wireless Bluetooth Firmware to provide native Bluetooth in macOS.
The firmware binary files are from the Linux Open Source Project.

macOS 26.5: This branch adds a second hook for IOUSBHostPipe::initWithDescriptorsAndOwners using the ConfigurationDescriptor mangled symbol. Required for BLE HID pairing on Tahoe 26.5 with Intel 8087:0026 (and similar). Classic BT was unaffected; LE-only devices timed out without this patch.

## Documentation

**Please read the docs carefully before using the Kernel Extensions or submitting an Issue Report!**

- [Supported Devices](https://openintelwireless.github.io/IntelBluetoothFirmware/Compat.html)
- [Installation](https://openintelwireless.github.io/IntelBluetoothFirmware/Installation.html)
- [Frequently Asked Questions](https://openintelwireless.github.io/IntelBluetoothFirmware/FAQ.html)
- [Troubleshooting](https://openintelwireless.github.io/IntelBluetoothFirmware/Troubleshooting.html)

## Credits

- [torvalds/linux](https://github.com/torvalds/linux)
- [acidanthera/BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM)
