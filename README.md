# System Monitoring and Application Health Checker

## Overview
This project implements two Linux administration and monitoring tasks using Python:

1. System Health Monitoring Script
2. Application Health Checker

## Objective 1: System Health Monitoring Script

### Features
- Monitors CPU usage
- Monitors memory usage
- Monitors disk usage
- Counts running processes
- Generates alerts when thresholds are exceeded
- Logs system health information

### Technologies Used
- Python
- psutil
- logging

---

## Objective 2: Application Health Checker

### Features
- Checks application availability
- Verifies HTTP status codes
- Detects whether the application is UP or DOWN
- Handles connection failures gracefully

### Technologies Used
- Python
- requests

---

## Installation

Install dependencies:

```bash
pip install -r requirements.txt
