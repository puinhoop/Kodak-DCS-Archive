# Windows 10/11 Compatibility

This directory contains instructions to install and run the original Kodak Professional DCS Camera Manager 4.2 on modern versions of Microsoft Windows.

## Instructions

1. Download and install the [original Kodak Professional DCS Camera Manager 4.2](https://github.com/puinhoop/Kodak-DCS-Software-Archive/blob/main/windows-software/camera-manager/4.2/original/Camera_Manager_V_4_2.exe).

2. Once the installation process has finished, restart your computer as asked by the installer.

3. Navigate to:

   `C:\Program Files (x86)\Kodak\KODAK DCS Photo Desk\`

4. Right-click `CamMan.exe` and select **Properties**. On the **Compatibility** tab, enable **Run this program in compatibility mode for:**, and select **Windows XP (Service Pack 3)** from the drop-down list. Click **Apply**, and then **OK** to save the changes. After enabling Windows XP SP3 compatibility, Camera Manager will correctly detect its bundled camera drivers.
   
5. Replace the original `kodakcms.dll` (version 5.1.1.0) with the [newer version](https://github.com/puinhoop/Kodak-DCS-Software-Archive/blob/main/windows-software/photo-desk/4.3/compatibility/windows-10-11/kodakcms.dll) (5.2.5.0).

## Tested

- Windows 10 x64
- Windows 11 x64

## Copyright Notice

Kodak Professional DCS Camera Manager and Kodak Professional ColorFlow CMM are copyrighted software.

All trademarks and copyrights remain the property of their respective owners.

This repository preserves historical Kodak DCS software and documentation for archival, research and interoperability purposes.

