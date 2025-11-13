# Cyber Internship Task 1

**Tool Used:** Nmap  
**Date:** 13-Nov-2025  
**Purpose:** Network scanning of 10.211.81.0/24 for Cyber Security Internship Task 1  
**Files:** task1_nmap.txt

## Summary of Findings
- Open ports discovered
- Services running on each host
- Possible vulnerabilities (if any)
- Recommendations: Close unused ports, update services, enable firewall

## Commands Executed
```bash
nmap -sS 10.211.81.0/24 -oN task1_nmap.txt
