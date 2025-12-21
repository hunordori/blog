---
title: My Homelab Setup
date: 2025-11-02 12:00:00 +/-0000
categories: homelab hardware
tags: homelab list     # TAG names should always be lowercase
description: Hardware that I use in my homelab setup.
image:
  path: assets/img/posts/2025/11/2025-11-02-my_homelab/20250922__MG_2522_homelab.jpg
  alt: My homelab setup
---


# Hardware

## Networking

- Topton N100 mini PC (64GB/8GB) as pfSense
- Unifi CloudkeyG2 (with SSD) - Unifi Controller and Unifi Protect
- Unifi Pro Max 48 PoE - main switch
- Unifi Aggregation - connecting servers
- Unifi Flex Mini 2.5 GbE (Desk)
- Unifi Flex Mini (Backup)
- Unifi U7 XG

## Storage

- Synology DS920 (4x10 TB HDD) + 8 TB External HDD (for backup)
- Supermicro (Custom 2U) (2x8 TB HDD and 6x1 TB SSD)

## Servers

### Aero

- Supermicro SYS-5019S-MT (1U)
- E3-1230 v6 @ 3.50GHz
- 64 GB RAM
- 2x 64 GB SATA DOMs
- 1x 1 TB Nvme SSD
- 1x 1 TB Sata (WD RED SSD)
- 1x 1 TB HDD
- Intel (Dell) X710 2-port SFP+

### MTB

- Minisforum MS-01
- Intel i9-12900H
- 96 GB RAM
- 56 GB Intel Nvme SSD (OS)
- 2 TB Nvme SSD
-

### Proxmox

- Lenovo M720q 1L PC
- Intel i5-6500T
- 32 GB RAM
- 1 TB Nvme SSD

# Misc

- FanPico (Custom fan and LED controller)
- Esp32 temperature sensors
- UZG-1 PoE ethernet Zigbee controller
- APC Backup Pro (main UPS)
- several Sonoff S31 plugs for power monitoring

# Backup and Notification

- GLiNet Spitx (GL-X750) for LTE connection
- Raspberry Pi 4 for NUT and notifications
- APC Back-UPS ES 650G1

# Software

- Proxmox VE 9 as Hypervisor
- HomeAssistant for home automation
- Wazuh
- InfluxDB v2
- Grafana 12
- Docker
- Zabbix
- PostgresDB
- Gitlab CE
- Ansible
- Uptime Kuma

![My homelab setup](assets/img/posts/2025/11/2025-11-02-my_homelab/20250922__MG_2559_homelab.jpg)
_My homelab setup_
