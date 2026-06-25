
# SIGMA - Security Information Gathering and Monitoring System

## Overview

SIGMA (Security Information Gathering and Monitoring System) is a lightweight host-based security monitoring solution developed for Windows environments. The system automates security event collection, threat detection, alert management, and reporting to assist security analysts and administrators in identifying suspicious activities.

This project was developed as part of the Bachelor of Science in Networking and Cyber Security at ISBAT University.

---

## Problem Statement

Security analysts often face large volumes of system logs and alerts, making it difficult to identify genuine threats quickly. Existing solutions are either too basic, such as Windows Event Viewer, or too expensive and complex, such as enterprise SIEM platforms.

SIGMA was developed to bridge this gap by providing a lightweight, affordable, and easy-to-deploy monitoring solution.

---

## Objectives

### Main Objective

To develop a Security Information Gathering and Monitoring System (SIGMA) that automates security monitoring and threat detection on Windows systems.

### Specific Objectives

* Study existing security monitoring solutions.
* Gather system requirements.
* Design and develop SIGMA.
* Test and evaluate system performance.

---

## Features

* Windows Event Log Collection
* Real-Time Process Monitoring
* Network Connection Monitoring
* Rule-Based Threat Detection
* Alert Management
* VirusTotal Integration
* PDF Report Generation
* CSV Export
* Web-Based Dashboard
* Natural Language Query Support

---

## Technologies Used

* Python
* Flask
* PyWin32
* Psutil
* Bootstrap 5
* ReportLab
* JSON Storage
* VirusTotal API

---

## System Architecture

SIGMA collects data from:

* Windows Event Logs
* Running Processes
* Active Network Connections
* Threat Intelligence Sources

The collected information is processed through the Rule Engine, which generates alerts and reports through the web dashboard.

---

## Installation

1. Clone the repository

git clone https://github.com/fortunategody/SIGMA.git

2. Navigate to project folder

cd SIGMA

3. Install dependencies

pip install -r requirements.txt

4. Run the application

python app.py

5. Open browser

http://localhost:5000

---

## Testing

The system was tested using simulated attack scenarios including:

* Multiple Failed Login Attempts
* Suspicious PowerShell Execution
* Unauthorized Network Connections

All detection rules performed successfully during testing.

---

## Limitations

* Windows-only support
* Single-host monitoring
* No user authentication
* Rule-based detection only
* Limited VirusTotal API requests

---

## Future Improvements

* Multi-host monitoring
* Role-based authentication
* Machine Learning Detection
* Automated Response Actions
* Linux and macOS Support

---

## Authors

* Forturatus Abure Gabriel Toppo


ISBAT University
Bachelor of Science in Networking and Cyber Security
2026
