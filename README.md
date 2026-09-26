# Sunset downloads

[Sunset](https://sunset-public.onrender.com) is a free AI assistant for chatting, schoolwork, code and writing. This
page holds the downloads.

## Sunset for Windows

**[Download Sunset-Setup.exe](https://github.com/FlakeSap/sunset-downloads/releases/latest/download/Sunset-Setup.exe)**
(version 1.0.2, about 107 MB, Windows 10 and 11, 64-bit)

- The installer lets you choose where Sunset is installed.
- The app is Sunset in its own window. It opens the live site, so you always get the newest Sunset.
- **It updates itself.** From version 1.0.2 the app checks for a newer version in the background and installs it when
  you close it, so the next time you open it, it is the new version and you never need to download it again. If you
  have an older version (1.0.0 or 1.0.1), install this one over it once by hand; your sign-in is kept.
- Each release also holds `latest.yml` and `Sunset-Setup.exe.blockmap`. The app reads those to update itself; you do
  not need to download them.
- **Windows may warn "unknown publisher" or "Windows protected your PC"**, because the app isn't code-signed yet.
  Choose **More info**, then **Run anyway**.
- To remove it, use Windows Settings, then Apps, then Sunset, then Uninstall.

### Check your download (optional)

The SHA-256 of `Sunset-Setup.exe` (version 1.0.2) is:

```
409C6AB6970CCA5C24771CEE2C1F5DD360182F52B61D214A236FED4238611928
```

In PowerShell: `Get-FileHash .\Sunset-Setup.exe -Algorithm SHA256`

## Other ways to use Sunset

- In your browser: https://sunset-public.onrender.com
- Installed from Chrome or Edge as its own window (the install icon in the address bar)
