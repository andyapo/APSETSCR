# APSETSCR
**CMD window size and color utility**
---------------------------------

APSETSCR is a small Command line utility which is able to quickly set window
size, buffer and get basic info about it's dimensions and colors.

This is the first public release of APSETSCR.  

---

## Usage

- `APSETSCR set <cols> <rows> <buffer>`
- `APSETSCR max <buffer>`
- `APSETSCR info`

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
51 288 bytes<br>
**SHA-256**:<br>
0e8535ba1d1ff66ce9cffd5ef5d4a32890952a7326a0ec0c2b3d8ad8925e323b<br>

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
