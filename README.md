# ts-encfs

ts-encfs automates the process of mounting an encrypted EncFS folder

## What does it do

This module allows you to make use of EncFS encryption virtual file system on your Android device. [Wikipedia](https://en.wikipedia.org/wiki/EncFS)

Its main objective is to automate the mounting process so that the encrypted files are automatically mounted and available for you on device boot and accessible by Android.

Note that automated implementation is less secure if your Android device do not have encryption enabled. More in Technical section on website.

ts-encfs borrows the algorithm that is used by [ts-binds](https://www.technosparks.net/pages/product-documentation/ts-binds) in order to minimise user setup and also to handle the quirks of SDCardFS emulation

## Requirements

- Moderate knowledge on Linux workings
- FUSE support
- SDCardFS emulation for Internal and External storages
  - Android version ≥ 8
  - Android version = 7 **if** SDCardFS is enabled by user
- EncFS Magisk Module
  - Or your own-built binaries into `/system/xbin`
- Magisk Stable version ≥17
  - Beta and Canary version not supported

## Notice

This repository is currently under development, consider the module as of alpha stage.

## Links

## Changelog (2 recent versions)

_none_