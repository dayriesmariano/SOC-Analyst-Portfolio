#Day 3 Threat Landscape & Mitre Attack

## Objective
To understand common cyber threats handled by a SOC and learn how the MITRE ATT&CK framework helps SOC analysts identify and classify attacker 

## What is Threat Landscape?
The threat landscape refers to the collection of cyber threats that organizations face, including malware, phishing, insider threats, and advanced persistent threats (APT).

## Common Threats Monitored by SOC
- Phishing attacks
- Malware infections
- Brute-force login attempts
- Insider threats
- Ransomware attacks

## Introduction to MITRE ATT&CK
MITRE ATT&CT is a globally accessible kwowledge base of adversary tactics and techniques based on real-world observations.

## MITRE ATT&CK Structure
- Tactics: the attacker's goal (e.g., Initial Access, Execution)
- Techniques: how the attacker achieves the goal
- Sub-techniques: More detailed attack methods

## Example: Failed Login Alert Mapping
Scenario: Multiple failed login attempts detected from a single IP address.

- Tactic: Credential Access
- Technique: Brute Force (T1110)
- SOC Action: Investigate source IP, check account lockouts, escalate if needed.

## Key Takeaways
- SOC analysts rely on MITRE ATT&CK to understand attacker behavior
- Mapping alerts to ATT&ck improves detection and response
- Threat landscape awareness helps prioritize alerts
