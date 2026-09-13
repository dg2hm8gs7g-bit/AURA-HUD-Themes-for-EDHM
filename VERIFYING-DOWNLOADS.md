# Verifying downloads

Each release includes `manifest.json` containing the SHA-256 checksum of every
individual theme ZIP.

On Windows PowerShell:

```powershell
Get-FileHash -LiteralPath '.\AURA - Guardian Relic.zip' -Algorithm SHA256
```

Compare the displayed hash with the matching entry in `manifest.json`.
