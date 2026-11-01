Legacy Evolved Remote Configuration

This repository hosts the encrypted remote configuration used by Legacy Evolved.

Configuration File

- "Config.enc" — AES-encrypted configuration payload.
- Format: Base64-encoded AES-CBC ciphertext.
- Encryption compatibility: SHA-256 key derivation, zero IV, PKCS7 padding.

Updates

The Android application retrieves "Config.enc" through GitHub Raw.

Only encrypted configuration data should be published here.
