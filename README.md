# Fedora38-linux

Microsoft Intune Portal installer adapted for Fedora 38.

Based on Microsoft's [installer.sh](https://github.com/microsoft/shell-intune-samples/blob/master/Linux/Intune%20Installer/installer.sh) (MIT License, Copyright (c) Microsoft Corporation).

Microsoft does not publish `intune-portal` in its Fedora repos, so on Fedora 38 the script uses the RHEL 9 repo. This is unofficial and unsupported by Microsoft.

## Usage

```bash
curl -fsSLO https://raw.githubusercontent.com/NCBrady/Fedora38-linux/main/installer.sh
chmod +x installer.sh
./installer.sh --verbose
```

Options: `--insiders-fast`, `--local-package <path>`, `--verbose`, `-h|--help`.
