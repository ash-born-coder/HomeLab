# HomeLab - Atlas

**A personal HomeLab for exploring Linux, networking, self-hosting, automation, and embedded systems.**

## Overview

Atlas started with a second-hand Lenovo ThinkCentre M83 and the idea of building my own infrastructure. It has since developed into a centralized system for server administration, container management, and performance monitoring.

The project focuses on learning through practical implementation, troubleshooting, and continuous improvement.

## Hardware

| Component | Specification |
|---|---|
| System | Lenovo ThinkCentre M83 |
| Processor | Intel Core i5-4590 |
| Memory | 8 GB DDR3 |
| Storage | Samsung 500 GB SSD |
| OS | Ubuntu Server 26.04 LTS |
| Network | Gigabit Ethernet |

## Applications & Services

| Application | Purpose | Status |
|---|---|---|
| OpenSSH | Remote administration | Operational |
| UFW | Firewall | Configured |
| Cockpit | Server management | Operational |
| Docker & Compose | Container deployment | Operational |
| Portainer | Container management | Operational |
| Node Exporter | System metrics | Operational |
| Prometheus | Metric collection | Operational |
| Grafana | System visualization | Operational |
| Pi-hole | External DNS filtering | Operational |
| Samba | Network file sharing | Pending |

## System Architecture

Atlas combines native Linux services and Docker containers, alongside a dedicated Raspberry Pi running Pi-hole.

![HomeLab Architecture](assets/architecture/homelab-architecture.png)

## What I'm Working Towards

The goal is to develop a centralized **HomeLab Control Center** for infrastructure management, automation, and embedded device integration.

![HomeLab Monitoring Dashboard](assets/grafana/images/15-system-dashboard.png)

Future developments include:

- Raspberry Pi and ESP32 integration.
- Service availability monitoring and alerts.
- Secure remote access and automation.
- Backup, restoration, and recovery testing.

## Documentation

Implementation details, configuration files, screenshots, and troubleshooting notes are available in the [Services directory](services/).

## Technologies

`Linux` `SSH` `Networking` `Docker` `Docker Compose` `Prometheus` `Grafana` `PromQL` `Pi-hole` `YAML`

---

*An ongoing personal engineering project focused on learning by building, experimenting, and improving.*
