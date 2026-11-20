# HomeLab - Atlas

**A personal HomeLab for exploring Linux, networking, self-hosting, automation, and embedded systems.**

## Overview

I started this project with a second-hand Lenovo ThinkCentre M83 and the idea of turning an ordinary desktop computer into something more useful.

Rather than relying entirely on cloud services, I wanted to understand how to build and manage my own infrastructure. What began as a simple Ubuntu server is gradually becoming a central system for file storage, media streaming, monitoring, and connecting my Raspberry Pi and ESP32 projects.

The goal isn't just to get different applications running. It's to understand how they work, how they communicate, and how to maintain a reliable system that I can continue improving.

## Hardware

| Component | Specification |
|---|---|
| System | Lenovo ThinkCentre M83 |
| Processor | Intel Core i5-4590 |
| Memory | 8 GB DDR3 |
| Storage | Samsung 500 GB |
| Operating System | Ubuntu Server 26.04 LTS |
| Network | Gigabit Ethernet |

## Applications & Services

The HomeLab brings together several applications, each serving a different purpose.

| Application | Purpose | Status |
|---|---|---|
| Ubuntu Server | Main operating system | Completed |
| OpenSSH | Remote server administration | Completed |
| UFW | Firewall and network security | Configured |
| Cockpit | Browser-based server management | Installed |
| Samba | File sharing across the local network | Configured |
| Docker & Compose | Running containerized applications | Installed |
| Jellyfin | Personal media streaming | Deployed |
| Prometheus | System and application metrics | Planned |
| Grafana | Monitoring dashboards and visualization | Planned |
| Node Exporter | Linux hardware and performance metrics | Planned |
| Uptime Kuma | Service availability monitoring | Planned |
| Tailscale | Secure remote access | Planned |
| Node-RED | Automation and IoT workflows | Planned |
| Mosquitto MQTT | Communication with embedded devices | Planned |
| InfluxDB | Time-series data storage | Planned |

## System Architecture

The HomeLab is built around a single Ubuntu server, with native Linux services and Docker containers working alongside one another.

As the project develops, I plan to connect Raspberry Pi devices, ESP32 microcontrollers, and monitoring agents to create a more complete infrastructure.

A detailed architecture diagram will be added as the system expands.

## What I'm Working Towards

One of my main goals is to develop a centralized **HomeLab Control Center**.

Instead of opening separate interfaces for every application, I want a dashboard that gives me a clear picture of the entire system, including:

- Server health, CPU, memory, storage, and network activity.
- Docker containers and their running status.
- Availability of services such as Samba and Jellyfin.
- Monitoring data collected through Prometheus and Grafana.
- Connected Raspberry Pi and ESP32 devices.
- A graphical representation of how the services and devices communicate.

I also plan to explore automation, secure remote access, backup strategies, and better ways to deploy and maintain applications.

## Documentation

This repository is both a record of the HomeLab and a place to document what I learn while building it.

I'll be adding configuration examples, architecture diagrams, screenshots, troubleshooting notes, and explanations of the decisions made throughout the project.

The idea is to keep everything organized and reproducible, so that I can rebuild parts of the system or expand it without starting from scratch.

## Technologies

`Linux` `Ubuntu Server` `SSH` `Networking` `Docker` `Docker Compose` `Samba` `Jellyfin` `Prometheus` `Grafana` `Python` `Raspberry Pi` `ESP32` `MQTT`

---

*An ongoing personal engineering project focused on learning by building, experimenting, and improving.*
