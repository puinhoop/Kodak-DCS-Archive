# 12-bit DCR Compatibility

This directory contains a replacement `DCSPro4SLR.dll` required to properly handle 12-bit DCR files in Kodak DCS Photo Desk 4.3.

## Credits

[Alexey Danilchenko](https://github.com/Alexey-Danilchenko) has developed [custom firmware 5.4.10 for Kodak DCS Pro cameras](https://github.com/Alexey-Danilchenko/Kodak-DCS-Tools/tree/master/Firmwares#kodak-dcs-14nx-slrn-%D0%B8-slrc-firmwares) that changes the 10-bit lossy compression of DCR files to lossless 12-bit. In order to properly handle these 12-bit DCR files in Photo Desk 4.3, he has also developed a [patched version of the orginal DCSPro4SLR.dll](https://drive.google.com/open?id=0Bw2ZohnbXtyAYThyUXh0NDBNSUE). 

The `DCSPro4SLR.dll` included in this directory is **identical** to Alexey Danilchenko's original patched version and is redistributed here solely to ensure its long-term preservation and availability.

## File Information

| Property | Value |
|----------|-------|
| Filename | `DCSPro4SLR.dll` |
| File description | Software toolkit for the DCS Pro 14 series of cameras |
| File version | 2.6.1.3 |
| Product name | Kodak Professional DCS Pro 4 SLR SDK |
| Product version | 2, 6, 1, 3 |
| File size | 512 kB |
| Language | English (United States) |
| Original filename | `DCSPro4SLR.dll` |
| Architecture | x86 (32-bit) |
| SHA-256 | A4500C8C15A877D1F4258506A769A011A6B0D6873EB33DF11F317772244F3D42 |
| VirusTotal | https://www.virustotal.com/gui/file/A4500C8C15A877D1F4258506A769A011A6B0D6873EB33DF11F317772244F3D42 |

## Installation

1. Make sure that [Photo Desk 4.3](https://github.com/puinhoop/Kodak-DCS-Software-Archive/tree/main/windows-software/photo-desk/4.3/original) is installed and completely closed before proceeding.

2. Navigate to:

   `C:\Program Files (x86)\Kodak\KODAK DCS Photo Desk\`

3. Rename the existing `DCSPro4SLR.dll` to `DCSPro4SLR-original.dll`.

4. Download the [replacement DCSPro4SLR.dll](https://github.com/puinhoop/Kodak-DCS-Software-Archive/blob/main/windows-software/photo-desk/4.3/compatibility/12-bit-DCR/DCSPro4SLR.dll) and copy to `C:\Program Files (x86)\Kodak\KODAK DCS Photo Desk\`.

5. The replacement DCSPro4SLR.dll makes Photo Desk 4.3 only supporting 12-bit DCR files. In case you need to open non 12-bit raw files, first rename `DCSPro4SLR.dll` to `DCSPro4SLR-12bit.dll` and then `DCSPro4SLR-original.dll` to `DCSPro4SLR.dll`.

## Tested

- Windows 10 x64
- Windows 11 x64

## Copyright Notice

Kodak Professional DCS Pro 4 SLR SDK is copyrighted software.

All trademarks and copyrights remain the property of their respective owners.

This repository preserves historical Kodak DCS software and documentation for archival, research and interoperability purposes.
