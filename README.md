# Climate-KIC AI Playbook — Claude Onboarding Guide

Password-protected HTML guide hosted via GitHub Pages.

The page is AES-encrypted client-side using [StatiCrypt](https://github.com/robinmoisson/staticrypt). Visitors enter the password to decrypt in their browser — the plaintext never leaves the device.

## View

Open the GitHub Pages URL and enter the password (shared separately).

## Re-encrypt with a new password

```bash
npx staticrypt source.html -p 'NEW_PASSWORD' --short -o index.html
```
