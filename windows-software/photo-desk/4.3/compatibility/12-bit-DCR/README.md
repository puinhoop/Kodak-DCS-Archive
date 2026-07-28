# 12-bit DCR Compatibility

This directory contains a replacement `DCSPro4SLR.dll` required to properly handle 12-bit uncompressed DCR files.

## Credits

[Alexey Danilchenko](https://github.com/Alexey-Danilchenko) has developed [custom firmware 5.4.10](https://github.com/Alexey-Danilchenko/Kodak-DCS-Tools/tree/master/Firmwares#kodak-dcs-14nx-slrn-%D0%B8-slrc-firmwares) that changes the 10-bit lossy compression of DCR files to lossless 12-bit. In order to properly handle these 12-bit DCR files in Photo Desk 4.3, he has also developed a [patched version of the orginal DCSPro4SLR.dll](https://drive.google.com/open?id=0Bw2ZohnbXtyAYThyUXh0NDBNSUE).     
