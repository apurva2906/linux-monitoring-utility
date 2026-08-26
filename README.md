# Linux System Monitoring Utility

A Bash-based Linux monitoring utility created to practice Linux commands, Bash scripting, command processing, and basic system monitoring.

## Project Overview

This project collects and displays essential Linux system information through a simple Bash script.

### Metrics Monitored

| Metric | Linux Command / Tool |
|---|---|
| Hostname | `hostname` |
| Uptime | `uptime` |
| CPU Usage | `top` |
| Memory Usage | `free` |
| Disk Usage | `df` |
| IP Address | `hostname -I` |

## Bash & Linux Concepts Practiced

- Bash variables
- Command substitution
- Pipes (`|`)
- `grep`
- `awk`
- `top`
- `free`
- `df`
- File permissions
- Basic Bash scripting
- Linux troubleshooting

## Sample Output

The script produces a snapshot of the Linux system:

```text
Linux System Monitoring Utility
Hostname: ...
Uptime: ...
Memory Usage: ...%
Disk Usage: ...%
IP Address: ...
CPU Usage: ...%
