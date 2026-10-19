# Protector for Windows v1.9.0 Beta 1

**A Dean Design & Software product** · Powered by Aver Production

## What's new

- Optional basic adult-content protection (disabled by default)
- Interface language selection: English, Turkish, Spanish
- Classic, Navy and F-35 themes
- Branding, UI and version-display improvements
- Improved installation and upgrade experience

## Testing

The development team's functional and installer upgrade QA passed on Windows, covering installation, upgrades from v1.8.2, website blocking, adult-filter on/off, themes, languages, and persistence of settings.

## Known limitations

- **Beta release:** Issues may remain.
- Adult-content protection blocks a basic domain list; it is **not** comprehensive filtering.
- The Windows installer is **unsigned** and may trigger Windows SmartScreen warnings. SHA-256 verification does not provide code-signing assurance.

## Download

Public release will include:
- `Protector-Setup-1.9.0-beta.1.exe`
- `SHA256SUMS.txt`

Installer expected SHA-256, obtained from the private GitHub draft-release asset metadata:

```text
be456cd9fb241dfc911ee0d58f553693573ee7a9e756bc62370403cb0bcd65eb
```

Check it locally with PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 ".\Protector-Setup-1.9.0-beta.1.exe"
```

If the actual installer hash differs, **stop publication and investigate**.

Support: https://dean-design-software.netlify.app/support.html
