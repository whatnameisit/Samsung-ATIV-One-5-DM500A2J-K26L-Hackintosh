# Changelog
August 1, 2021
- Deleted Wireless USB Big Sur Adapter because the USB dongle is very unstable.

July 25, 2021
- Disable hibernation and use normal sleep because hibernation fails sometimes.

As of May 30, 2021
- QE/CI works with HD 7750.
- Wi-Fi and Bluetooth upgraded with USB devices and adapters.
- Use hibernation `25` instead of normal sleep `0` because the former would turn off the computer and the dGPU light whereas the latter will still have dGPU light on.
- Added FileVault support in configuration. Enable FileVault in Settings-Security and Privacy-FileVault.
