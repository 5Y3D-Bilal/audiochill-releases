# Audio Chill releases

Audio Chill is a Windows app. This repository hosts its official downloads, add-ons and signed update feed.

## Download

Get the latest files from the [Releases page](https://github.com/5Y3D-Bilal/audiochill-releases/releases/latest). Each release includes:

- `AudioChill_Setup_<version>_win64.exe`: the Windows installer
- `AudioChill_<version>_win64.zip`: the Windows package
- `AudioChill_<version>_win64.sha256`: the SHA-256 checksum for the package
- `AudioChill-addon-<name>_<version>_win64.zip`: optional add-ons
- `latest` and `latest.sig`: the signed update feed

## Supported platforms

- Windows 64-bit

## Verify and update

Check the package against its checksum, for example with `Get-FileHash .\AudioChill_<version>_win64.zip -Algorithm SHA256` in PowerShell, and compare the result with the value in the `.sha256` file.

## Website

The download page for Audio Chill is [audiochill-website](https://github.com/5Y3D-Bilal/audiochill-website).

## Source code

This repository contains no source code, only download files and the update feed.
