# sirrvault/scoop-bucket

Scoop bucket for Sirr — the ephemeral secret manager (Windows).

## Install

```powershell
scoop bucket add sirrvault https://github.com/SirrVault/scoop-bucket
scoop install sirrvault/sirrd   # Server daemon
scoop install sirrvault/sirr    # CLI client
```

## Packages

| Package | Description |
|---------|-------------|
| `sirrd` | Sirr daemon — self-hosted secret vault server |
| `sirr`  | Sirr CLI — push, get, and manage secrets from the terminal |

## Mac/Linux

Use Homebrew: `brew tap sirrvault/tap`
