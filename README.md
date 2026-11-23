
# 🖥️ Proxmox Home Lab – IT Infrastructure & Systems Administration

## Overview

Welcome to my home lab!

I built this dedicated server to gain hands-on experience with IT infrastructure, virtualisation, networking, Linux and Windows administration, and troubleshooting.

The goal is to create a practical learning environment where I can experiment with different technologies, solve technical problems and develop skills relevant to IT support and systems administration.

This is an ongoing project that I'll continue expanding as I learn.

---

## Server Hardware

| Component | Specification |
|-----------|---------------|
| CPU | AMD Ryzen 7 7700 |
| Motherboard | ASUS TUF Gaming B650E-E WiFi |
| RAM | Kingston Fury Beast 32GB DDR5-6000 |
| Storage | Lexar NM990 2TB NVMe SSD |
| Power Supply | Corsair RM850e 850W |
| Case | Lian Li LANCOOL 217 |
| Graphics | AMD Ryzen 7 7700 Integrated Graphics |

---

## Current Environment

| Component | Configuration |
|-----------|---------------|
| Hypervisor | Proxmox VE 9 |
| Hostname | pve.home.arpa |
| Networking | Ethernet, bridged networking (vmbr0) |
| Management | Proxmox Web Interface |
| Virtual Machines | Ubuntu Server 26.04 LTS |
| Remote Access | SSH from Windows PowerShell |

---

## Project Documentation

| Project | Description | Status |
|---------|-------------|--------|
| 01 – Hardware Build | Component selection, physical assembly and initial setup | ✅ Completed |
| 02 – Proxmox Installation | Hypervisor installation, networking, repositories and updates | ✅ Completed |
| 03 – Ubuntu Server | VM deployment, network configuration, updates and SSH | ✅ Completed |
| 04 – Linux Administration | Users, groups, permissions, services and troubleshooting | ⏳ Planned |
| 05 – Windows Virtual Machines | Windows installation and administration | ⏳ Planned |
| 06 – Backups & Recovery | Snapshots, backups and restoration testing | ⏳ Planned |
| 07 – Networking | Network services, VLANs and infrastructure expansion | ⏳ Planned |

---

## Troubleshooting & Lessons Learned

Building this home lab i had to deal with some encounters. Some of the issues are:

- **Installation Media:** Downloaded an incompatible ARM64 installer instead of the x86-64 version.
- **Network Connectivity:** Troubleshot an inaccessible Proxmox web interface caused by a disconnected Ethernet cable.
- **Repository Errors:** Resolved HTTP 401 errors by configuring the appropriate Proxmox and Ceph no-subscription repositories.
- **Remote Administration:** Configured and verified SSH access to an Ubuntu Server virtual machine.

Each issue has helped me develop a better understanding of troubleshooting, system configuration and IT infrastructure.

---

## Skills & Technologies

- Proxmox VE and virtualisation
- Computer hardware and server assembly
- Linux and Ubuntu Server
- TCP/IP networking and DHCP
- SSH and remote administration
- Virtual machine deployment
- System updates and package management
- Technical troubleshooting and documentation

---

## Future Plans

As the lab develops, I plan to explore:

- Windows Server and Active Directory
- Windows 11 virtual machines
- Network monitoring and logging
- Backups and disaster recovery
- Docker and containerisation
- Network segmentation and VLANs
- Cybersecurity and security hardening

---

*This repository documents my ongoing journey of learning, building and troubleshooting real IT infrastructure.*
