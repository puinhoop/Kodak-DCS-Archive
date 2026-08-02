# 12-bit DCR Compatibility

The replacement `DCSPro4SLR.dll` developed by [Alexey Danilchenko](https://github.com/Alexey-Danilchenko) in order to properly handle 12-bit DCR files in Kodak DCS Photo Desk 4.3, can be used for Camera Manager 4.2 as well.

## Installation

1. Make sure that [Camera Manager 4.2](https://github.com/puinhoop/Kodak-DCS-Software-Archive/tree/main/windows-software/camera-manager/4.2/original) is installed and completely closed before proceeding.

2. Navigate to:

   `C:\Program Files (x86)\Kodak\KODAK DCS Camera Manager`

3. Rename the existing `DCSPro4SLR.dll` to `DCSPro4SLR-original.dll`.

4. Download the [replacement DCSPro4SLR.dll](https://github.com/puinhoop/Kodak-DCS-Software-Archive/blob/main/windows-software/photo-desk/4.3/compatibility/12-bit-DCR/DCSPro4SLR.dll) and copy to `C:\Program Files (x86)\Kodak\KODAK DCS Camera Manager`.

5. The replacement DCSPro4SLR.dll makes Camera Manager 4.2 only supporting 12-bit DCR files. In case you need to open non 12-bit raw files, first rename `DCSPro4SLR.dll` to `DCSPro4SLR-12bit.dll` and then `DCSPro4SLR-original.dll` to `DCSPro4SLR.dll`.

## Tested

- Windows 10 x64
- Windows 11 x64

## Copyright Notice

Kodak Professional DCS Pro 4 SLR SDK is copyrighted software.

All trademarks and copyrights remain the property of their respective owners.

This repository preserves historical Kodak DCS software and documentation for archival, research and interoperability purposes.
