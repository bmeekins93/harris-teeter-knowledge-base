# Store Knowledge Base

A password-protected internal reference site.

The published page is **encrypted end-to-end**: the content is scrambled with AES-256 (a key derived from a shared password via PBKDF2-SHA-256, 250,000 iterations) and only decrypts in the browser after the correct password is entered. Without the password, the page shows only a lock screen and the page source contains nothing but ciphertext.

## What's in this repo

- `index.html` — the encrypted site (lock screen + ciphertext only).

Plaintext content and the underlying source documents are **intentionally kept out of this repository**.

## Updating the content

The content is authored from an internal source document, then encrypted before publishing. To change it: update the source, re-run the offline encryption tool to produce a new `index.html`, and commit it. Publishing the site keeps working automatically.
