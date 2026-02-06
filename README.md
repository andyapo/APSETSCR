# APSETSCR
**Simple CMD window managment utility**
---------------------------------

APSETSCR is a small Command line utility which is able to quickly set window
size, buffer, position and get basic info about it's dimensions and colors.

---

## Usage

- `APSETSCR --set-window <cols> <rows> <buffer>`
- `APSETSCR --set-position [x<winx>|y<winy>]`
- `APSETSCR --maximize <buffer>`
- `APSETSCR --info`

---

## Requirements

- ![Static Badge](https://img.shields.io/badge/Required-lightgreen?style=flat-square) Microsoft Windows

---


## Security Notice

APSETSCR is distributed as plain Batch source code and is signed

---

### Integrity Check

☝️To ensure the file has not been tampered with, verify its size and SHA-265 cheksum.<br>
**Size:**<br>
52 312 bytes<br>
**SHA-256**:<br>
127163bd69a40077fa61db02ac2d99ba763b4833970ae12c50004b4eb48c58bc<br>

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
