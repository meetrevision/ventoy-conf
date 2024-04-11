# Revision Configuration for Ventoy

This is a test repository for automating some parts of the Windows installation process using Ventoy Auto Install Plugin.

## Features

- OOBE configuration
  - Disable online account creation
  - Hide the Network screen
  - Disable the Privacy screen
- Custom Script
  - Disable automatic drivers updating
  - Pause Windows Updates
  - AllowTelemetry to 0
  - Prevent automatic Teams installation
  - Disable WPBT
  - Prevent Automatic Device Encryption
  - Disable Smart App Control
- Disable CEIP and Error Reporting
- Disable dynamic updates and diagnostic data during Windows PE

## Usage

1. Download the latest release of [Ventoy](https://github.com/ventoy/Ventoy/releases)
2. Configure Secure Boot and partition style
3. Install Ventoy
4. Copy the contents of this repository to the root of the Ventoy drive
5. Move your Windows ISO file(s) to the `WinISO` folder
6. Boot into Ventoy and select your ISO file
