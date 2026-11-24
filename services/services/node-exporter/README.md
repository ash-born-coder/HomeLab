# Node Exporter

Node Exporter is responsible for collecting hardware and operating system metrics from my HomeLab server.

## Implementation

The service was deployed using Docker Compose with read-only access to the host filesystem.

![Node Exporter deployment](../../assets/node-exporter/images/04-node-exporter-deployment.png)

| Configuration | Value |
|---|---|
| Port | 9100 |
| Network mode | Host |
| Filesystem access | Read-only |
| Restart policy | Unless stopped |

## Host Network Monitoring

During implementation, I noticed that the default Docker bridge configuration only reported container network interfaces rather than the physical Ethernet interface.

Switching to host networking resolved this limitation, allowing Node Exporter to collect traffic statistics from `eno1`. A restricted UFW rule was added to allow Prometheus to retrieve these metrics.

The collected data includes CPU utilization, memory, storage, temperature, uptime and network activity.

## Integration

System metrics are collected and stored by [Prometheus](../prometheus/).
