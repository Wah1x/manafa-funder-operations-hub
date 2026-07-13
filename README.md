# Manafa — Funder Operations Hub

Internal reference for Aramco SCF funder availability, published via GitHub Pages.

**Access is password-protected.** The published `index.html` is an AES-256 encrypted
page: it contains only ciphertext and a small loader. Nothing renders — and nothing
can be read in "view source" — without the access password, which is entered in the
browser and never stored server-side. The password is shared with approved viewers only.

## Editing

The human-readable source is **not** committed to this public repo (see `.gitignore`).
To change content, edit the plaintext `app.src.html` locally, then re-encrypt and
rebuild `index.html`. Ask the maintainer for the build steps and the current password.
