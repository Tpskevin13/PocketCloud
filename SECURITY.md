# Security Policy

## Supported Versions

| Version | Supported |
| ------- | --------- |
| 1.0.0   | ✅        |

## Reporting a Vulnerability

If you discover a security vulnerability in PocketCloud, please **do NOT open a public issue**.

Instead, report it privately by opening a [GitHub Security Advisory](https://github.com/Tpskevin13/PocketCloud/security/advisories/new).

Please include:
- A description of the vulnerability
- Steps to reproduce it
- Potential impact
- Your suggested fix (optional)

You can expect a response within **7 days**. If the vulnerability is confirmed, a fix will be released as soon as possible and you will be credited in the release notes.

---

## Security Features

PocketCloud was built with security in mind:

- 🔒 JWT authentication with 24h token expiration
- 🔑 BCrypt password hashing
- 🛡️ Brute-force protection (5 attempts = 15 min lockout)
- 🔐 Credentials stored in EncryptedSharedPreferences
- 🚫 Path traversal attack protection
- 📡 All communication over local network or Tailscale VPN

---

## VirusTotal Reports

Both APKs have been scanned and verified clean:

- [PocketCloud Client](https://www.virustotal.com/gui/file/48879a071e3b5a6fe4d1e89a5496bfc691942420ee66a10bf1c2e0c663cf885e)
- [PocketCloud Server](https://www.virustotal.com/gui/file/f2662adc7a3c2bc6069afdee7577d5aa78693e551a0a03bd7b90cd0cc139cedf)
