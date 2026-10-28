# Demarcus Miller | System Admin |

I'm a person who believes infrastructure work only matters if someone else can understand it. My focus is building practical, real-world Azure environments — then documenting them in a way that speaks to engineers *and* the business stakeholders who need to know why it matters.

Below are ten labs. The newest five are built in Azure and centered on identity and access: how accounts are created, moved, synced to the cloud, restricted and secured. Underneath them is my earlier five-part portfolio, built end-to-end in Azure, covering the core pillars of enterprise IT operations: **identity → network visibility → log aggregation → process → vulnerability management.**

## 🛠️ Tech Stack

`Azure` `Windows Server` `Active Directory` `Wireshark` `Splunk` `ServiceNow` `Nessus` `PowerShell` `Linux` `Terraform` `Microsoft Entra ID` `Entra Cloud Sync` `Azure RBAC` `Azure Key Vault` `Azure CLI` `Group Policy` `NTFS / SMB`

## 📂 Featured Projects

**Newest: identity and access**

### 🗂️ Lab 1 — Identity Lifecycle on Active Directory
One domain controller and twenty users, taken through joiners, movers, leavers and an audit against least privilege. Every script runs from outside with a dry-run switch.

🔗 [View Repository →](https://github.com/dmill1mb/azure-iam-lifecycle-lab)

### ☁️ Lab 2 — Entra Cloud Sync (builds on Lab 1)
Copies the active users from Lab 1 to Microsoft Entra ID on the free tier, scoped by OU. A synced user is forced to register for MFA, and the lab shows that Remote Desktop to the domain controller still asks for none.

🔗 [View Repository →](https://github.com/dmill1mb/entra-cloud-sync-lab)

### 🔒 Lab 3 — Azure RBAC Access Control
Three identities, three roles, one virtual machine, deployed with Terraform and tested by signing in as each identity.

🔗 [View Repository →](https://github.com/dmill1mb/azure-rbac-access-control-lab)

### 📁 Lab 4 — NTFS File Server
Active Directory, NTFS permissions and SMB file services on Azure, deployed with Terraform and configured with PowerShell.

🔗 [View Repository →](https://github.com/dmill1mb/Azure-ntfs-file-server-lab)

### 📲 Lab 5 — Entra ID MFA
Multi-factor authentication on the free Entra ID tier: registration, number matching, sign-in and audit logs, revoking sessions and a passkey.

🔗 [View Repository →](https://github.com/dmill1mb/azure-entra-mfa-lab)

---

**Earlier portfolio: visibility, detection and vulnerability management**

### 🔐 Lab 1 — Active Directory Deployment
Stood up a Windows Server 2025 domain controller in Azure, configured Group Policy Objects, and joined client machines to the domain — establishing the identity foundation the rest of this portfolio builds on.

🔗 [View Repository →](https://github.com/dmill1mb/Lab-1-Active-Directory)

### 📡 Lab 2 — Network Traffic Analysis with Wireshark
Captured and decoded live traffic to break down DNS resolution, TCP handshakes, and the difference between HTTP and HTTPS at the packet level — turning raw captures into a plain-language explanation of what's actually happening on the wire.

🔗 [View Repository →](https://github.com/dmill1mb/Lab-2-WireShark-Network-analysis)

### 📊 Lab 3 — SIEM Implementation with Splunk
Forwarded Windows event logs to a Linux-based Splunk Enterprise instance, simulated real security events (account lockouts, failed logins), and built custom dashboards and alerts to surface them in real time.

🔗 [View Repository →](https://github.com/dmill1mb/Lab-3-Splunk)

### 🎫 Lab 4 — ITSM Workflow with ServiceNow
Managed the full incident lifecycle in a ServiceNow Personal Developer Instance — service catalog requests, change management, and reporting dashboards — modeling how IT operations run day to day.

🔗 [View Repository →](https://github.com/dmill1mb/Lab-4-ServiceNow)

### 🛡️ Lab 5 — Vulnerability Management with Nessus
Deployed Nessus on an Azure Ubuntu Server VM, discovered CVE-2013-3900, and remediated it via a PowerShell registry fix across both the 64-bit and WOW64 paths — closing the loop from scan to fix.

🔗 [View Repository →](https://github.com/dmill1mb/Lab-5-Nessus-Vulnerability-Scanning)

## 📫 Let's Connect

📄 Resume: [Demarcus Miller Resume (PDF)](https://github.com/user-attachments/files/31583126/Demarcus.Miller.Resume.1.pdf)

💼 LinkedIn: [www.linkedin.com/in/miller-demarcus](https://www.linkedin.com/in/miller-demarcus)

📱 Phone: (501) 502-3477

✉️ Email: [millersdemarcus@gmail.com](mailto:millersdemarcus@gmail.com)
