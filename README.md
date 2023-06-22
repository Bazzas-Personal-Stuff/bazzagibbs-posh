# Posh Powershell theme by BazzaGibbs

A simplified theme based off `powerlevel10k_classic`.

Designed for use with the Nord color scheme, but may work with other schemes.

## Setting theme

1. Install oh-my-posh
2. Install posh-git
3. Add the following to `$PROFILE`

```ps
Import-Module posh-git
oh-my-posh init pwsh --config "<path\to\bazzagibbs.omp.json>" | Invoke-Expression
$env:POSH_GIT_ENABLED = $true
```
