# 🔐 API Response AES Decryptor

A lightweight, browser-based tool for decrypting and analyzing encrypted API responses during **API Security Testing, AppSec, and penetration testing**.

The tool combines **AES-CBC decryption, HMAC-SHA256 verification, automatic format detection, and Burp Suite response extraction** into a single web interface.

## 🚀 Live Demo

**Try the tool:**  
[https://mstr-creta.github.io/YOUR-REPOSITORY-NAME/](https://mstr-creta.github.io/aes-api-decryptor/)

---

## ✨ Features

### 🔑 AES Decryption

- AES-128
- AES-192
- AES-256
- AES-CBC decryption
- PKCS#7 padding
- Multiple IV layouts
- Automatic IV/layout detection

### 🔒 HMAC Verification

- HMAC-SHA256 verification
- Expected vs calculated HMAC comparison
- Detects HMAC mismatches
- Displays verification status

### 🧩 Automatic Detection

Automatically probes:

- Key encoding
- Prefix length
- Input normalization
- IV layout
- Response format

Supported key formats:

- UTF-8
- Hex
- Base64

### 📥 Burp Suite Import

Paste a complete Burp Suite HTTP request/response or response body.

The tool can automatically extract:

```text
RESPONSE_DATA
RESPONSE_TOKEN
