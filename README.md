# Pogama — Windows installers

Official download files for [Pogama](https://pogama.xyz), a desktop workspace for AI and code.
This repository only hosts installers; it contains no source code.

**Download:** see [Releases](../../releases) or [pogama.xyz/download](https://pogama.xyz/download).

## Install

1. Download `Pogama-<version>-Windows-x64.zip` from the latest release.
2. Extract it and run `Pogama-Installer.exe`.
3. If Windows SmartScreen shows "Windows protected your PC", choose **More info → Run anyway**.

Requirements: Windows 10 or 11 (x64). Installed copies update themselves from inside the app.

Each release lists the SHA-256 of its zip so you can check the download:

```powershell
Get-FileHash .\Pogama-0.2.5-Windows-x64.zip -Algorithm SHA256
```

App developed by Pocho.dev
