# AutoSysAdmin
Cross-platform IT systems automation with PowerShell and Python — automate account lifecycle, patching, log analysis, and fleet health reporting.
# 🚀 AutoSysAdmin

Cross-platform IT systems automation with **PowerShell** and **Python** — automate account lifecycle, patching, log analysis, and fleet health reporting.

---

## ✨ Features
- 👤 **Account Lifecycle (PowerShell + AD)**: Bulk create/disable users from CSV, group assignment, OU placement, and auditing.
- 🖥 **Patch Management**:
  - Windows updates with `PSWindowsUpdate`.
  - Linux updates with `apt`, `dnf`, or `yum`.
- 📊 **Log Analysis**: Export and analyze Windows Event Logs (failed logins, critical errors).
- ❤️ **Health Reporting**: Collect CPU, memory, disk, and service status, then generate an aggregated HTML fleet report.

---

## 🛠 Quickstart

### Clone repository
```bash

python -m venv .venv
# Windows
.\.venv\Scripts\activate
# Linux/macOS
source .venv/bin/activate
pip install -r python/requirements.txt

PowerShell setup (Windows)
Install-Module ActiveDirectory -Scope AllUsers -Force
Install-Module PSWindowsUpdate -Scope AllUsers -Force

AutoSysAdmin/
  powershell/
    account_manager.ps1      # Bulk AD user management
    patch_windows.ps1        # Windows patching
    export_eventlog.ps1      # Export logs
    healthcheck.ps1          # Windows health check
    modules/AutoSysAdmin.psm1
    samples/users.csv
  python/
    patch_linux.py           # Linux patching
    log_analyzer.py          # Analyze logs
    health_agent.py          # Collect host health
    report_builder.py        # Merge HTML report
    requirements.txt
  configs/settings.example.json
  reports/ (generated)
  tests/test_log_analyzer.py
  README.md
  LICENSE
  .gitignore


git clone https://github.com/<your-username>/AutoSysAdmin.git
cd AutoSysAdmin
