# Protector for Windows

**Official Windows downloads for Protector**  
A [Dean Design & Software](https://dean-design-software.netlify.app/) product · Powered by Aver Production

Protector helps you block distracting websites and control which sites you can access on Windows.

## Downloads

**Protector v1.9.0 Beta 1 — available now as a public prerelease.**

- **[Download Protector for Windows v1.9.0 Beta 1 (.exe)](https://github.com/test2deploy/protector-downloads/releases/download/v1.9.0-beta.1/Protector-Setup-1.9.0-beta.1.exe)**
- [View public prerelease and release notes](https://github.com/test2deploy/protector-downloads/releases/tag/v1.9.0-beta.1)
- [Download SHA-256 checksum file](https://github.com/test2deploy/protector-downloads/releases/download/v1.9.0-beta.1/Protector-Setup-1.9.0-beta.1.exe.sha256.txt)

**Beta software:** This installer is unsigned and Windows SmartScreen may warn you. Download only from the official release linked above.

## Beta 1 features

- Website blocking and custom site management
- Optional **basic** adult-content domain blocking, disabled by default
- English, Turkish, and Spanish
- Classic, Navy, and F-35 themes
- Updated UI and installer / upgrade improvements

Functional and installer-upgrade QA has passed on the tested Windows build. This is still beta software.

## Installer integrity

Installer filename: `Protector-Setup-1.9.0-beta.1.exe`

Installer SHA-256, matching the published GitHub Release asset metadata:

```text
be456cd9fb241dfc911ee0d58f553693573ee7a9e756bc62370403cb0bcd65eb
```

After downloading, verify the installer in PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 ".\Protector-Setup-1.9.0-beta.1.exe"
```

Compare all 64 characters with the digest above. **If it does not match, do not run the installer.**

## Security and limitations

- Optional adult-content blocking uses a basic domain list, not comprehensive filtering.
- This beta is **not digitally signed**. Windows SmartScreen may warn when the installer runs. A matching SHA-256 confirms file integrity against the published value, but **does not** replace publisher code signing.
- This repository distributes compiled release assets only; Protector's source repository remains private.

## Support

[Contact Dean Design & Software](https://dean-design-software.netlify.app/support.html)

**Human-built. Human-tested. Human-supported.**
