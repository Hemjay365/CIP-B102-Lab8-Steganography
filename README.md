# CIP-B102 Lab 8 -- Steganography and Hidden Data Analysis

Student: Mary-Joy Adewole
Registration Number: 2025/FWSD/11468
Course: SBT-DF202 -- Computer and Digital Forensics

## Contents

- `CIP-B102_Lab8_Report_Mary-Joy_Adewole.pdf` / `.docx` -- full forensic report
- `screenshots/` -- all 13 supporting screenshots (Figures 1-13 in the report)
- `hash_records/all_hashes.txt` -- every SHA-256 hash recorded during the practical
- `secret_files/` -- the two secret text files, reconstructed exactly from their
  full on-screen content (`secret.txt`, `Mary-Joy_Adewole_hidden_note.txt`)
- `wordlists/` -- the two custom wordlists used with StegSeek, reconstructed
  exactly from their full on-screen content (`lab4_wordlist.txt`, `my_wordlist.txt`)
- `stego_images/` -- placeholder; add the actual BMP files here (see below)


## Summary

Two full steganography exercises were performed with Steghide (embed/extract)
and StegSeek (passphrase recovery via wordlist), one guided and one
independently authored. Both were verified via SHA-256 hashing and diff,
confirming lossless embedding/extraction, and both stego images were
successfully cracked by StegSeek using a custom wordlist containing the
correct passphrase.
