# AutoSysAdmin — IT Systems Automation Toolkit

**Shiva Subedi** | PowerShell • Python • Active Directory • Windows • Linux • IT Operations

> Cross-platform systems administration automation for account lifecycle, patching, event-log analysis and infrastructure health reporting.

## Project at a Glance

| Automation Area | Capability |
|---|---|
| Account Lifecycle | Bulk AD user creation/disablement, OU placement and group assignment |
| Windows Patching | PowerShell-based Windows Update workflow |
| Linux Patching | Python automation for apt, dnf and yum environments |
| Log Analysis | Windows Event Log export and failed-login/error analysis |
| System Health | CPU, memory, disk and service-status collection |
| Reporting | Aggregated infrastructure health reporting |

## Why I Built This

System administrators repeatedly perform tasks such as account provisioning, patch checks, log review and system-health validation. This project demonstrates how I approach those tasks as repeatable automation rather than manual one-off work.

## Repository Structure

```text
AutoSysAdmin/
├── powershell/
│   ├── account_manager.ps1
│   ├── patch_windows.ps1
│   ├── export_eventlog.ps1
│   ├── healthcheck.ps1
│   ├── modules/
│   └── samples/
├── python/
│   ├── patch_linux.py
│   ├── log_analyzer.py
│   ├── health_agent.py
│   ├── report_builder.py
│   └── requirements.txt
├── configs/
├── reports/
├── tests/
└── README.md
```

## Administration Workflows

### Active Directory Account Management
The PowerShell workflow is designed around repeatable identity administration: read approved user information, process account actions, place users in the appropriate OU/groups and produce auditable output.

### Patch Management
Windows and Linux workflows demonstrate how patch operations can be standardized across different operating systems while keeping platform-specific tooling separate.

### Event Log Analysis
Windows Event Logs can be exported for analysis of authentication failures and system errors, helping turn raw logs into actionable troubleshooting information.

### Health Reporting
Host health collection focuses on operational signals such as CPU, memory, disk and services. Python components aggregate information for reporting.

## Skills Demonstrated

`PowerShell` `Python` `Active Directory` `Windows Server` `Linux` `Automation` `Patching` `Event Logs` `System Monitoring` `Troubleshooting` `IT Operations`

## Safe Use

Review scripts, dependencies, privileges, paths and configuration before execution. Test administrative automation in a lab environment before considering use against production systems.

## Related Portfolio Projects

- [Enterprise Windows Server & Active Directory Administration](https://github.com/shivasubedii/enterprise-windows-active-directory-lab)
- [Microsoft 365 | Entra ID | Intune Administration](https://github.com/shivasubedii/microsoft-365-entra-intune-enterprise-lab)
- [Zero Trust Network Segmentation — Healthcare](https://github.com/shivasubedii/zero-trust-network-segmentation-healthcare)

---

**Shiva Subedi** — Computer Systems Technology | IT Support | Systems Administration | Cloud | Networking | Cybersecurity
