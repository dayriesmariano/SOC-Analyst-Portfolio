# Day 2 - SOC Workflow & Blue Team

## Overview
Day 2 focuses on understanding the SOC workflow in detail and the different between Blue Team, Red Team, and Purple Team. This helps in knowing where a SOC analyst fit.

## Day 2 Goals
- Learn Blue Team vs Red Team vs Purple Team
- Understand SOC workflow step-by-step
- Document a beginner-friendly scenario

## Blue Team vs Red Team vs Purple Team
- Red Team: Offensive security, simulates attackers, tools like Metasploit, Nmap.
- Blue Team: Defensive security, protects system, analyzes alerts, monitors logs (SOC Analyst)
- Purple Team: Collaboration between Red and Blue to improve detection.

SOC Workflow Steps
Log Collection: From servers, endpoints, network devices, and application.
Detection: Correlate logs using SIEM to detect suspicious activity.
Alert Triage: Determine if alerts are false positives or real threats.
Investigation: Analyze scope and impact of the incident.
Response: Actions like blocking IPs, isolating systems, or resetting credentials.
Documentation: Record incident details for reporting and learning

Exampe Scenario - Failed Login Alert
- Multiple failed login attempts from the same IP
- Short time interval triggers alert

SOC Analyst Action
1. Check logs for source IP and affected accounts
2. Escalate if suspicious activity confirmed
3. Document incident

