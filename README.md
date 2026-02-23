# Windows Enterprise Homelab

This project documents the creation of my Windows 11 enterprise-style homelab using VMware Fusion on Apple Silicon. I used a Linux-based Active Directory Domain Controller using Samba on Ubuntu Server.
The lab focuses on identity management, authentication, logging, privilege separation, and Active Directory fundamentals for cybersecurity learning.

## Environment
- Host: macOS (Apple Silicon)
- Hypervisor: VMware Fusion (ARM)
- Guest OS: Windows 11 (ARM)
- Account Type: Local administrator (offline provisioning)

## Domain Information
- Domain: CORP.LOCAL
- Hostname: linux-dc
- Role: Active Directory Domain Controller
- DNS Backend: Samba Internal
