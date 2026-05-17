# linux-log-analysis-monitoring

## Overview
This project demonstrates Linux system monitoring, log analysis, log rotation, and automation using Bash scripting and cron jobs on an Ubuntu server.

The assignment simulates real-world Linux administration and DevOps monitoring tasks by analyzing system logs, monitoring disk usage, automating alerts, and managing log files efficiently.

---

## Features

- Log rotation using logrotate
- Weekly log rotation with 4-week retention
- Log analyzer script for detecting system errors
- Disk monitoring and alert generation
- Automated monitoring using cron jobs
- Bash scripting for system administration tasks

---

## Technologies Used

- Ubuntu Linux
- Bash Scripting
- Cron Jobs
- Logrotate
- Linux System Logs
- AWS EC2

---

## Project Structure

```text
linux-log-analysis-monitoring/
│
├── README.md
│
├── report/
│   └── assignment-2-report.pdf
│
├── screenshots/
│   ├── 01-application-log.png
│   ├── 02-logrotate-config.png
│   ├── 03-logrotate-output.png
│   ├── 04-log-analyzer-script.png
│   ├── 05-log-analyzer-output.png
│   ├── 06-disk-monitor-script.png
│   ├── 07-disk-monitor-output.png
│   └── 08-cron-jobs.png
│
├── scripts/
│   ├── log-analyzer.sh
│   └── disk-monitor.sh
│
└── configs/
    └── application-logrotate.conf
