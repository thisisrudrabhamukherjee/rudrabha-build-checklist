# Verifying a copy

These instructions confirm that a copy of Rudrabha Mukherjee's Build Checklist is unmodified.

## Published fingerprint (version 1.5.1)

| File | Bytes | SHA-256 |
|---|---|---|
| `Rudrabha-Mukherjee-Build-Checklist_v1.5.1.html` | 235368 | `1de3243d9da23aa503521c3fc496e7a0eb58d2879fa4209007a12d4277f1cc41` |

The same bytes are served as `index.html` at the repository root and at the live address.

The fingerprint verifies the HTML file. An installed copy on your device cannot be hashed directly in the same way; save the page from inside the app, or download from `releases/`, and check that file.

## Commands

Linux or macOS:

```bash
shasum -a 256 Rudrabha-Mukherjee-Build-Checklist_v1.5.1.html
```

Windows PowerShell:

```powershell
Get-FileHash Rudrabha-Mukherjee-Build-Checklist_v1.5.1.html -Algorithm SHA256
```

The output must match the hash above exactly. The file must end with a single newline character.

## Inside the app

The Publisher screen shows the application's own fingerprint. Compare what you see there with the hash published here.

## If the values differ

Your copy has been changed. Do not treat it as the published release. Download again from this repository's `releases/` folder or from a trusted save you made yourself from the official address, and check the hash again.
