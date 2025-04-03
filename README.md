# 🔍 windows-target-1: Security Log Analysis Lab

## 🧪 Lab Description

This project simulates a real-world security investigation where an internal asset (`windows-target-1`) was discovered to have been internet-facing for 30 days.

Your role is to review log data for suspicious activity, identify potential unauthorized access, and report findings in a structured and repeatable way.

---

## 🎯 Objectives

- Identify failed and successful login attempts
- Detect brute-force or credential-stuffing behavior
- Determine whether unauthorized access occurred
- Correlate login events with remote IPs
- Report findings using MITRE ATT&CK techniques
- Provide actionable recommendations for hardening

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Report_Findings.txt` | Investigation results structured using MITRE ATT&CK |
| `LogonFailed.csv` | Redacted failed logon attempts to `windows-target-1` |
| `LogonSuccess.csv` | Redacted successful logon attempts |
| `MostActiveIPs.csv` | Summary of IPs with highest logon attempt volume |
| `Investigation.txt` | Core KQL queries used during investigation |

---

## 🛠️ Tools Used

- Microsoft Defender for Endpoint
- Microsoft Sentinel (Log Analytics)
- Kusto Query Language (KQL)
