# Posh Powershell theme by BazzaGibbs

A simplified theme based off `powerlevel10k_classic`.

Uses ANSI colors, designed for use with the Nord color scheme. May work with other schemes.

![image](https://github.com/Bazzas-Personal-Stuff/bazzagibbs-posh/assets/20216946/c0891205-d200-4e75-b5b2-3e6bca48e543)

## Setting theme

1. Install oh-my-posh
2. Install posh-git
3. Add the following to `$PROFILE`

```
Import-Module posh-git
oh-my-posh init pwsh --config "<path\to\bazzagibbs.omp.json>" | Invoke-Expression
$env:POSH_GIT_ENABLED = $true
```
