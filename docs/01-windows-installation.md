# Windows Installation & Offline Provisioning

## Objective
Deploy Windows 11 using offline provisioning to maintain identity control.

## Key Steps

- Installed Windows 11 ARM edition
- Disconnected network during OOBE
- Created local administrator account
- Avoided Microsoft cloud-based identity binding
- Because of the hardened OOBE, BYPASSNRO was ignored. So I had to force Windows to beleive there was no network hardware in the command prompt. Then I was able to create a local admin account, staging my machine in a secure environment. 

## Local Administrator Account

Account created:
- Username: localadmin
- Role: Local Administrator

## Evidence

![Boot Manager](../screenshots/02-efi-boot-from-install.png)
![Windows install](../screenshots/01-windows11-arm-install.png)
![OOBE bypass attempted](..screenshots/04-oobe-bypassnro.png)
![Network interface disabled](..screenshots/05-network-interface-disabled.png)
![Local administrator account created](..screenshots/06-localadmin-account-created.png)
![Initial desktop](../screenshots/03-initial-desktop.png)

