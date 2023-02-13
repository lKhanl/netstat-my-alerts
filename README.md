# netstat-my-alerts

## Description

- These are my alerts for [netdata](https://www.netdata.cloud/). They are based on
  the [netdata alerts](https://learn.netdata.cloud/docs/agent/health/reference#alerts)
  and [netdata alarms](https://learn.netdata.cloud/docs/agent/health/reference#alarms).
- The alerts are based on the [netdata documentation](https://learn.netdata.cloud/docs/agent/health/reference#alerts).

## Installation

- Copy the files to the netdata directory `/etc/netdata/health.d/`.
- Restart netdata.
- Check the alerts in the netdata dashboard.

## Alerts

- CPU Usage: when the CPU usage is above 70% for 5 minutes, the alert is triggered.
- RAM Usage: when the RAM usage is above 90% for 5 minutes, the alert is triggered.
- Disk Usage: when the disk usage is above 80% for 1 hour, the alert is triggered.
