# Rudrabha Mukherjee's Build Checklist

A single-file offline web app containing the complete process for building software with the help of an AI assistant, broken into thirteen stages and every step worth ticking off. It tailors the list to what the person is making.

**Live address:** https://rudrabha-build-checklist.pages.dev

## Getting a copy you can trust

The application is one HTML file. Anybody can save their own permanent copy from inside the app; that copy then works offline for good. To confirm a download is unmodified, check it against the published SHA-256 fingerprint. See [docs/VERIFYING-A-COPY.md](docs/VERIFYING-A-COPY.md).

Published fingerprint for version 1.11.0:

```
e8dfe26186e3f9b5bc5613298c2ff7f1e7f9333ddee9bfdcfa48978b647f5b0c
```

File size: 278308 bytes.

A versioned copy lives at [`releases/Rudrabha-Mukherjee-Build-Checklist_v1.11.0.html`](releases/Rudrabha-Mukherjee-Build-Checklist_v1.11.0.html) (published with each release).

## Installing

You can install Rudrabha Mukherjee's Build Checklist on your phone, tablet or computer so it opens like an app and works offline. See [docs/INSTALLING.md](docs/INSTALLING.md) for step-by-step instructions on Android, iPhone and iPad, Windows, macOS, and Ubuntu/Linux.

## What it does

- Thirteen stages covering the process of building software with an AI assistant, with every step worth ticking off, tailored to what you are making
- One self-contained HTML file â€” no libraries, frameworks, web fonts, icon sets or third-party code â€” so it keeps working when you have no internet, and so you can save the whole page as a single file
- Installable as a progressive web app; works offline once installed
- Your work is never sent over the network by the app itself; at a web address it may ask whether a newer version exists (you can switch that off in Settings)
- Your work is kept in the browser's `localStorage` on your own device; nothing is uploaded; no accounts, cookies, analytics or tracking
- Optional lock: AES-GCM-256 encryption of the saved record, with the key wrapped by a PIN (PBKDF2-SHA256, 250,000 iterations) and optionally by the answer to one recovery question (PBKDF2-SHA256, 1,200,000 iterations); answers are never stored. Setting a recovery question is optional: you can choose to rely on your PIN alone for maximum secrecy, or add a question as a safety net.
- Accessibility: minimum 44 px tap targets, 18 px base text, adjustable text size, light and dark themes, no horizontal scrolling from 320 px to 1920 px, no WCAG AA contrast failures
- British English throughout
- Verified for tap sizes, colour contrast, offline use from disk, and safe upgrade of saved work

## How to run it

Download the HTML file and open it in any modern browser, visit the live address above, or install it to your device. There is no build and no server to run.

## Accessibility and browser support

Works in current browsers that support the Web Crypto API (needed only if you use the lock). Tested for reading and tapping from 320 px wide phones up to 1920 px screens. Text size and colour themes are adjustable inside the app.

## How your work is stored

Your work lives in this browser, under the web address you opened the page from. A different address, a different device, or a cleared browser means an empty start. Use the in-app **Move or back up my work** screen to put everything into one file so it can travel.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Security reports: [SECURITY.md](SECURITY.md).

## Licence and copyright

BSD 3-Clause. Copyright (c) 2026, Rudrabha Mukherjee. See [LICENSE](LICENSE) and [NOTICE](NOTICE). Cryptography notice: [CRYPTOGRAPHY-NOTICE.md](CRYPTOGRAPHY-NOTICE.md). Privacy: [PRIVACY.md](PRIVACY.md). Terms: [TERMS.md](TERMS.md).
