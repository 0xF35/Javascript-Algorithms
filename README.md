# 🔐 Collection Of Javascript Algorithms: 

#### This repository provides implementations of cryptographic hashing algorithms: **SHA-1**, **SHA-256**, and **SHA-512**. 

#### Hashing is widely used in security-related applications, such as data integrity, password hashing, and digital signatures.

### Supported Algorithms:
- **SHA-1** (⚠️ Insecure, included for legacy support)
- **SHA-256** (🔒 Secure, widely used)
- **SHA-512** (🔐 High-security with longer hash output)

---

## 🚀 Quick Start

| Algorithm  | Description                          | Hash Size       |
|------------|--------------------------------------|-----------------|
| **SHA-1**  | Legacy algorithm (not secure)        | 160 bits (20 bytes) |
| **SHA-256**| Secure, widely used (SHA-2 family)   | 256 bits (32 bytes) |
| **SHA-512**| Secure with larger output (SHA-2)    | 512 bits (64 bytes) |

---

## 📖 Usage 

### 🔐 SHA-1

The **SHA-1** algorithm produces a 160-bit hash value (20-byte). _Although **SHA-1** is no longer considered secure for cryptographic purposes_, it is still used in some legacy systems.


    console.log(Sha1.hash('hash this string'));
    // Output: 91aebc21fa63504351c19cc2add5e04478664d94

### 🔐 SHA-256

The SHA-256 algorithm, part of the SHA-2 family, produces a 256-bit hash value (32-byte). It is commonly used in security protocols, blockchain, and data integrity verification.

    console.log(Sha256.hash('hash this string'));
    // Output: eedb752a1e7a2691ebd896ce86d868c5ddc795419be5925030cbee768153700b

### 🔐 SHA-512

The SHA-512 algorithm, also part of the SHA-2 family, generates a 512-bit hash value (64-byte). It provides enhanced security and is used in applications that require a larger hash output.

    console.log(Sha512.hash('hash this string'));
    // Output: c9779fc579ebd199744f1004..........a5cc9cd35af7a0e53




| Algorithm  | Use Case                               | Recommendation          |
|------------|----------------------------------------|-------------------------|
| **SHA-1**  | Legacy systems, backward compatibility | ⚠️ Avoid if possible     |
| **SHA-256**| Security, blockchain, certificates     | 👍 Recommended           |
| **SHA-512**| File integrity, high-security apps     | 🔐 Highly recommended     |




Feel free to submit any issues or questions as well!
📢 Notes

    The implementations provided here are for educational purposes and may not be optimized for all production-level security applications.
    For secure, modern cryptographic solutions, consider using well-maintained libraries like:

    
crypto-js
js-sha3

### ❗ Disclaimer

### ⚠️ SHA-1 is considered broken and unsafe for most cryptographic applications. It has been included in this repository for educational and legacy purposes only.

For secure applications, use SHA-256 or SHA-512 instead.
