# Cryptographic Solutions

## Objectives
- Understand common cryptographic concepts
- Explain encryption, hashing, digital signatures, certificates, and PKI
- Connect cryptography to confidentiality, integrity, authentication, and non-repudiation

## Table of Contents

1. [Cryptography](#cryptography)
2. [Encryption](#encryption)
3. [Symmetric and Asymmetric Encryption](#symmetric-and-asymmetric-encryption)
4. [Hashing](#hashing)
5. [Digital Signatures](#digital-signatures)
6. [Certificates and PKI](#certificates-and-pki)
7. [Common Cryptographic Use Cases](#common-cryptographic-use-cases)
8. [Key Management](#key-management)
9. [Key Takeaways](#key-takeaways)

## Cryptography

- **Cryptography:** Techniques used to protect information by transforming it or proving its authenticity and integrity.
- Cryptography supports confidentiality, integrity, authentication, and non-repudiation.

## Encryption

- **Encryption:** Converts readable data into unreadable form using a key.
- **Plaintext:** Original readable data.
- **Ciphertext:** Encrypted unreadable data.
- **Decryption:** Converts ciphertext back into plaintext using the correct key.

Example:
- A laptop drive is encrypted so data is protected if the laptop is stolen.

## Symmetric and Asymmetric Encryption

- **Symmetric Encryption:** Same key is used to encrypt and decrypt.
  - Faster and useful for large amounts of data.
  - Example: AES.

- **Asymmetric Encryption:** Uses a public key and private key pair.
  - Public key can be shared.
  - Private key must be protected.
  - Example: RSA, ECC.

## Hashing

- **Hashing:** Converts data into a fixed-length value.
- Hashing is one-way and is used to verify integrity.

Examples:
- Verify downloaded file integrity
- Store password hashes instead of plaintext passwords
- Compare evidence without changing original data

## Digital Signatures

- **Digital Signature:** Uses cryptography to prove authenticity, integrity, and non-repudiation.

Digital signatures help prove:
- Who signed the data
- Data was not changed
- Sender cannot easily deny signing

## Certificates and PKI

- **Certificate:** Digital document that binds an identity to a public key.
- **PKI:** Public Key Infrastructure; system for creating, managing, distributing, and revoking certificates.
- **CA:** Certificate Authority; trusted entity that issues certificates.

Certificates are used for:
- HTTPS websites
- VPN authentication
- Email encryption
- Device identity
- Code signing

## Common Cryptographic Use Cases

- TLS for secure web traffic
- VPN encryption
- Full-disk encryption
- File encryption
- Password hashing
- Digital signatures
- Secure email
- Certificate-based authentication

## Key Management

- Keys must be protected because weak key management can break strong encryption.

Good practices:
- Rotate keys
- Limit access to keys
- Store keys securely
- Revoke compromised certificates
- Separate duties for key management
- Use HSM or secure key vault when appropriate

## Key Takeaways

- Encryption protects confidentiality.
- Hashing verifies integrity.
- Digital signatures support integrity, authentication, and non-repudiation.
- Certificates and PKI help establish trust.