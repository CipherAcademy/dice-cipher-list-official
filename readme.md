# DiceCipher Origin Matrix

This repository contains the **official Origin Matrix** for the DiceCipher® system — the foundational, fixed reference grid used to generate unique, non-repeating **Cipher Matrices** through dice-based derivation.

DiceCipher is a completely offline, pen-and-paper encryption method that achieves **perfect secrecy** (mathematically unbreakable one-time pad encryption) using only ordinary dice and paper. No computers, apps, or electronics are required.

The system is detailed in the book:  
**DiceCipher: Unbreakable Off-Grid Encryption — How to Achieve Perfect Secrecy with One-Time Pads Using Only Dice**  
by Árpád Lehel Mátyus  
(available on [Amazon](https://www.amazon.com/dp/B0GFXZ4KPL))

## What is the Origin Matrix?

The Origin Matrix is the **static, never-changing starting grid** at the heart of DiceCipher.  
It serves as the deterministic but unpredictable reference from which every user's personal Cipher Matrix is derived via a series of fair dice rolls.

- **Purpose**: Ensures that — even though the derivation process uses randomness from dice — all generated matrices remain unique, non-repeating, and cryptographically strong when used correctly with one-time pad principles.
- **Format**: A large grid of digits/characters (typically 10×10 or larger blocks covering 0–9 mappings or letter substitutions).
- **Usage**: Do **not** use this matrix directly for encryption. Always derive your own working Cipher Matrix first using the dice procedure described in the book.

## Repository Contents

- `origin-matrix.txt` — Plain text version of the Origin Matrix (easy to copy/print/verify)
- `origin-matrix.md` — Markdown-formatted table for better GitHub viewing
- `origin-matrix.pdf` — (optional) Printable high-resolution version
- `LICENSE` — Public domain or CC0 dedication (to allow free use while preserving attribution to DiceCipher)

## How to Use This Matrix

1. Obtain a physical copy of the **DiceCipher** book for the complete step-by-step dice-rolling derivation protocol.
2. Roll dice (usually multiple 10-sided dice or combinations of d6) as instructed to select rows/columns/offsets from this Origin Matrix.
3. Build your personal **Cipher Matrix** — this becomes your private reference for encrypting/decrypting messages.
4. Use the derived matrix with one-time pad addition/subtraction (mod 10 or similar) on your plaintext → ciphertext.

**Important security rules** (from the book):
- Never reuse key material.
- Use truly random dice rolls (physical dice only — no digital RNG).
- Destroy used one-time key material after single use.
- Keep the derivation process and final matrix strictly secret.

## Why a Separate Repo?

- The Origin Matrix must remain **immutable and identical** for everyone using DiceCipher correctly.
- A dedicated, public repo allows easy verification, long-term archiving, and sharing without depending on personal websites or changing book editions.
- Users can fork/clone this repo or download the matrix file directly.

## Links & Resources

- Official DiceCipher website: https://dicecipher.com/
- Book on Amazon: https://www.amazon.com/dp/B0GFXZ4KPL
- Related tools (if available): Cipher Matrix Builder/generator references on the official site
- Author / project maintainer: [add your GitHub username or relevant contact if desired]

## License

This Origin Matrix is released under the **CC0 1.0 Universal** (Public Domain) license to the extent possible under law.  
You are free to use, copy, modify, distribute, and build upon it for any purpose — no attribution required, though linking back to DiceCipher or the book is appreciated.

**Note**: While the matrix itself is freely redistributable, the full DiceCipher encryption method, terminology, and procedures remain the intellectual framework of the book's author.

Questions or issues? Open an issue here or refer to the official DiceCipher resources.