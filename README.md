# AuthHub

## 📌 Status

This project is no longer actively developed and has been archived.

It was an exploration of centralized authentication system design concepts inspired by modern identity providers such as enterprise-grade authentication systems.

## ✨ Features

- E-Mail and password authentication
- Password breach check via HaveIBeenPwned
- Passkey-based authentication
- E-Mail verification flow
- Two-factor authentication (TOTP)
- Backup codes for 2FA recovery
- Security key / passkey-based 2FA
- Secure password reset with 2FA verification
- Login throttling and rate limiting

## 🚀 Setup

1. Create a `.env` file in the project root.
2. Generate a secure 128-bit encryption key (Base64 encoded, 16 bytes).
3. Set it as `ENCRYPTION_KEY`.

```env
ENCRYPTION_KEY="L9pmqRJnO1ZJSQ2svbHuBA=="
```

### Generate key (recommended)

```bash
openssl rand --base64 16
```

## 📌 Notes

- This project is archived and not intended for production use.
- It serves as a system design and security architecture prototype.
