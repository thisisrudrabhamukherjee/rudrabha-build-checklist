# Verifying a copy

These instructions confirm that a copy of Rudrabha Mukherjee's Build Checklist is unmodified.

## Published fingerprint (version 1.4.0)

| File | Bytes | SHA-256 |
|---|---|---|
| `Rudrabha-Mukherjee-Build-Checklist_v1.4.0.html` | 223546 | `6e25282d7e93d2d3dbaf5fcfab2a37150f2a1067e6853beb58a3138e49831f11` |

The same bytes are served as `index.html` at the repository root and at the live address.

## Commands

Linux or macOS:

```bash
shasum -a 256 Rudrabha-Mukherjee-Build-Checklist_v1.4.0.html
```

Windows PowerShell:

```powershell
Get-FileHash Rudrabha-Mukherjee-Build-Checklist_v1.4.0.html -Algorithm SHA256
```

The output must match the hash above exactly. The file must end with a single newline character.

## Inside the app

The Publisher screen shows the application's own fingerprint. Compare what you see there with the hash published here.

## If the values differ

Your copy has been changed. Do not treat it as the published release. Download again from this repository's `releases/` folder or from a trusted save you made yourself from the official address, and check the hash again.
