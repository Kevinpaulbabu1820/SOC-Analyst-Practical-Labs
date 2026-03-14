SOC Analyst Practice Labs

This repository contains my hands-on SOC analyst practice labs completed on platforms like TryHackMe and LetsDefend.

The goal of this repository is to document security investigations, threat detection techniques, and incident analysis while developing practical Blue Team skills.

Skills Practiced

Security Incident Investigation

Log Analysis

Threat Detection

SIEM Alert Analysis

Phishing Investigation

Malware Traffic Analysis

Brute Force Attack Detection

Lab Platforms
TryHackMe

Labs completed on TryHackMe focusing on:

Network traffic analysis

Threat detection

Blue team investigations

LetsDefend

SOC simulation labs including:

Alert investigation

Log analysis

Incident response

Repository Structure
soc-analyst-practice-labs
│
├── TryHackMe
│   ├── phishing-email-analysis
│   └── malware-traffic-analysis
│
└── LetsDefend
    ├── brute-force-attack-investigation
    └── suspicious-login-alert


Each lab includes:

README.md – Lab explanation and investigation steps

Screenshots – Investigation evidence (sanitized)

Detection Logic – How the threat was detected

Key Learnings – Important concepts learned

Example Lab Documentation

Each lab contains:

Objective

Understand and investigate the security alert.

Investigation Steps

Review the alert triggered in the SIEM

Analyze related logs

Identify suspicious activity

Determine whether the alert is a true positive or false positive

Detection Logic

Example detection rule:

Multiple failed login attempts

Same IP address targeting multiple accounts

Key Learnings

How brute force attacks appear in authentication logs

Importance of log correlation in incident investigation

Identifying malicious IP activity

Important Note

To maintain security and follow platform guidelines:

Flags are not included

Private IP addresses are sanitized

Sensitive data is removed

Learning Goal

To build practical experience in Security Operations Center (SOC) workflows and improve my ability to analyze and respond to security incidents.

Future Labs

More labs and investigations will be added as I continue practicing SOC analyst skills.
