# System Monitoring Project

## Overview

This project implements two system administration and monitoring tasks using Python:

1. System Health Monitoring Script
2. Application Health Checker

## Objective 1: System Health Monitoring Script

### Features

* Monitors CPU usage
* Monitors memory usage
* Monitors disk usage
* Counts running processes
* Generates alerts when predefined thresholds are exceeded

### Sample Output

CPU Usage: 9.1%
Memory Usage: 91.8%
Disk Usage: 61.4%
Running Processes: 328
ALERT: High Memory Usage!

---

## Objective 4: Application Health Checker

### Features

* Checks application availability using HTTP requests
* Verifies HTTP status codes
* Reports whether the application is UP or DOWN

### Sample Output

Application Status: UP
HTTP Status Code: 200

---

## Technologies Used

* Python
* psutil
* requests

---

## Installation

pip install -r requirements.txt

---

## Execution

python system_health.py

python app_health_checker.py

