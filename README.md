# APSETSCR

![Platform](https://img.shields.io/badge/Windows-blue)
![Release](https://img.shields.io/github/v/release/andyapo/APSETSCR)
![License](https://img.shields.io/github/license/andyapo/APSETSCR)
![Downloads](https://img.shields.io/github/downloads/andyapo/APSETSCR/total)
![Stars](https://img.shields.io/github/stars/andyapo/APSETSCR)

**Simple CMD window managment utility**
---------------------------------

APSETSCR is a small Command line utility which is able to quickly set window
size, buffer, position and get basic info about its dimensions and colors.

---

## Usage

- `APSETSCR --set-window <cols> <rows> <buffer>`
- `APSETSCR --set-position [x<winx>|y<winy>]`
- `APSETSCR --maximize <buffer>`
- `APSETSCR --info`
- `APSETSCR --display-info`

---

## Requirements

- ![Static Badge](https://img.shields.io/badge/Required-lightgreen?style=flat-square) Microsoft Windows

---


## Security Notice

APSETSCR is distributed as freeware and is signed

---

### Integrity Check

☝️To ensure the file has not been tampered with, verify its size and SHA-265 cheksum.<br>
**Size:**<br>
51 960 bytes<br>
**SHA-256**:<br>
3754d0569d5df6fad658d8f2a0e35fda78bab24564ca3e2244cbae90d8ae3cde<br>

To verify SHA-256, please run:<br>
**Command Prompt**:<br>
```bat
certutil -hashfile APSETSCR.exe SHA256
```

**PowerShell**:<br>
```powershell
Get-FileHash .\APSETSCR.exe -Algorithm SHA256
```

⚠️ If the checksum does not match, do not run the file and download the latest version directly from this repository.

---

## License

MIT License
© 2026 andyapo
