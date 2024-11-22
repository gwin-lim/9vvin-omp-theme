# 9vvin Oh-My-Posh Theme
This is a repository of "9vvin Theme" for Windows Terminal PowerShell 7 Oh-My-Posh and VS Code Integrated Terminal.
Its color scheme is based on BirdsOfParadise.

## Oh-My-Posh Theme Usages
### locally
Download `9vvin_omp_theme.json` and ...

```ps1
# Microsoft.PowerShell_profile.ps1
oh-my-posh init pwsh --config '~/9vvin_omp_theme.json' | Invoke-Expression
```

### remotely
```ps1
# Microsoft.PowerShell_profile.ps1
oh-my-posh init pwsh --config 'https://github.com/gwin-lim/9vvin-term-theme/9vvin_omp_theme.json' | Invoke-Expression
```

## VS Code Terminal Color Customization
1. Open VS Code's `settings.json`
2. Merge within `9vvin_vs_code_term_color.json` like ...
```json
{
  // ...
  "workbench.colorCustomizations": {
    "terminal.ansiBlack": "#573D26",
    "terminal.ansiBlue": "#5A86AD",
    // ...
  },
  // ...
}
```

## Windows Terminal Color Scheme Customization
1. Open Windows Terminal's `settings.json`
2. Copy `9vvin_win_term_color.json`'s contents
3. Paste into `Schemes` array like...
```json
{
  // ...
  "schemes": 
    [
      // ...
      {
          "background": "#2A1F1D",
          "black": "#573D26",
          // ...
      },
      // ...
    ]
  },
  // ...
```