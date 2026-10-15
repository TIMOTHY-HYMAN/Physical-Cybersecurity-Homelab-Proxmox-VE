# Physical-Cybersecurity-Homelab-Proxmox-VE
This project documents my transition from a VirtualBox-based virtual lab to a physical homelab running Proxmox VE on a Dell OptiPlex 7050.  The goal is to build practical experience with virtualization, Windows Server administration, Active Directory, Linux, networking, and vulnerability management.

Hardware

System: Dell OptiPlex 7050

CPU: Intel Core i5-6500T

Memory: 16 GB RAM

Storage: 512 GB NVMe SSD

Hypervisor: Proxmox VE 9.2

Completed Work

Installed Proxmox VE on physical hardware.

Created a bootable installation USB using Rufus.

Troubleshot disk detection by changing the BIOS SATA operation mode from RAID On to AHCI.

Selected and installed Proxmox on the internal NVMe SSD.

Configured the initial hostname and management network settings.

Investigated network connectivity and Intel Wi-Fi interface detection.

Current Status

Proxmox VE is installed and boots successfully. Management network connectivity remains in progress because the server is located away from the Quantum Fiber router.

Planned Work

Establish reliable network connectivity and access the Proxmox web interface.

Migrate the existing Windows Server 2022 and Ubuntu virtual machines.

Continue Active Directory and Group Policy practice.

Add Linux administration and vulnerability management labs.

Document future troubleshooting, configurations, and lessons learned.

Skills Demonstrated

Proxmox VE, virtualization, BIOS configuration, Linux command-line troubleshooting, storage administration, network diagnostics, and technical documentation.
