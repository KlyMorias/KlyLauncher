# KlyLauncher

KlyLauncher is a Minecraft launcher for Windows by KlyMorias and Kelvin.

## Download

Open the [latest GitHub release](https://github.com/KlyMorias/KlyLauncher/releases/latest) and download `KlyLauncher.exe` from **Assets**. The [release archive](https://github.com/KlyMorias/KlyLauncher/releases) lists earlier versions.

To verify the download, run this in PowerShell from the folder containing the file:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\KlyLauncher.exe
```

Compare the output with the SHA-256 shown beside the executable in the release’s **Assets** list. Each release has its own hash.

## Report a problem

Open a [GitHub issue](https://github.com/KlyMorias/KlyLauncher/issues/new) and include the launcher version, your Windows version, and the steps that trigger the problem. Include the exact error message if one appears. Remove account details and tokens from logs before attaching them.

This repository hosts the Windows release packages and their documentation.
