# Re-Mem Pro — Portable USB Edition

Official binary distribution repository for the **Portable USB Edition** of [Re-Mem](https://www.novvitech.com/products/re-mem).

[![Download Latest Release](https://img.shields.io/github/v/release/novvitech/Re-Mem-Portable-Releases?label=Download%20Portable%20v1.0.7&color=00c2a8)](https://github.com/novvitech/Re-Mem-Portable-Releases/releases/latest/download/Re-Mem-Portable.zip)
[![Official User Guide (PDF)](https://img.shields.io/badge/User%20Guide-PDF%20Manual-00796B.svg)](./docs/Re-Mem-Pro-User-Guide.pdf)
[![Platform: Windows 10 / 11](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(64--bit)-blue.svg)](https://www.novvitech.com/products/re-mem)
[![License: Commercial](https://img.shields.io/badge/License-Commercial%20%2F%20Free%20Evaluation-gold.svg)](https://www.novvitech.com/products/re-mem#remem-pricing)

---

## ⚡ Quick Start

1. Download **[`Re-Mem-Portable.zip`](https://github.com/novvitech/Re-Mem-Portable-Releases/releases/latest/download/Re-Mem-Portable.zip)**.
2. Extract the archive to any folder or directly onto a **USB flash drive**.
3. Double-click **`Re-Mem-Portable.exe`** to launch.
4. **Zero installation** and **zero administrator privileges** required.

All encrypted vault files, keys, and settings are stored locally in the adjacent `data/` folder (`data/vault.remem`) on your drive, leaving zero footprint on the host computer.

---

## 🔒 Cryptographic & Security Verification

| Property | Value |
| :--- | :--- |
| **File Name** | `Re-Mem-Portable.zip` |
| **Version** | `v1.0.7` |
| **OS Support** | Windows 10 & Windows 11 (64-bit) |
| **Size** | ~93.9 MB |
| **Encryption** | AES-256-GCM + Argon2id Memory-Hard KDF |
| **SHA-256 Checksum** | `CFA675DB7AB0E97F229625C6D69370237798BECF373E6B4FEF78F3862002AEF2` |

To verify the integrity of your download in Windows PowerShell:
```powershell
Get-FileHash -Algorithm SHA256 .\Re-Mem-Portable.zip
```

---

## 🛡️ Core Highlights

- **100% Offline Vault:** Secrets never touch external cloud servers, third-party databases, or telemetric trackers.
- **FIDO2 / WebAuthn Hardware Passkeys:** Built-in passkey manager supporting NIST P-256 credentials.
- **Live TOTP 2FA Authenticator:** Real-time 30-second countdown rings without requiring a phone app.
- **Developer Secrets & `.env` Manager:** Store and export environment variables in 1 click.
- **Tamper Auto-Destruct Shield:** 10 consecutive incorrect password attempts shreds the local vault to prevent brute-force attacks.
- **Printable Emergency Paper Kit:** Emergency rescue document with 32-character master recovery key and offline QR code.

---

## 🌐 Official Website & Licensing

- Official Website: [https://www.novvitech.com/products/re-mem](https://www.novvitech.com/products/re-mem)
- Microsoft Store Edition: [Get on Microsoft Store](https://apps.microsoft.com/detail/9pj2sskn63rm?hl=en-US&gl=IN)
- Built by **Novvi Tech Services**, Jaipur, Rajasthan, India.
