# Vulnerability Assessment Report - OWASP Juice Shop

## Objective

Conduct a read-only vulnerability assessment of the OWASP Juice Shop demo application to identify common web security weaknesses.


## Target

Website: https://demo.owasp-juice.shop/#/


## Scope

This assessment was limited to passive security testing only.

Allowed Activities:
- Nmap service enumeration
- OWASP ZAP passive scanning
- HTTP security header analysis
- Browser-based inspection

Not Performed:
- Exploitation of vulnerabilities
- Login bypass attempts
- Brute-force attacks
- Denial-of-Service (DoS) testing


## Tools Used

- Kali Linux 2025.2
- Nmap 7.95
- OWASP ZAP
- Firefox Developer Tools
- Git & GitHub


## Methodology

1. Performed network reconnaissance using Nmap.
2. Identified exposed services and their versions.
3. Conducted passive analysis using OWASP ZAP.
4. Reviewed HTTP response headers.
5. Documented findings with evidence and remediation recommendations.


## Findings Summary

| Finding                              |   Risk Level  |
|--------------------------------------|---------------|
| Missing Security Headers             |      Low      |
| Server Information Disclosure        |      Low      |
| Session Identifier Exposure in URL   |      Low      |
| Information Disclosure               | Informational |
|--------------------------------------|---------------|

## Repository Contents

### Evidence
Contains:
- Nmap scan outputs
- OWASP ZAP findings

### Screenshots
Contains:
- Nmap scan screenshots
- OWASP ZAP screenshots
- Security header analysis evidence

### Report
Contains:
- Final Vulnerability Assessment Report PDF


## Ethical Statement

This assessment was conducted strictly within a read-only scope for educational purposes. No exploitation, modification, or harmful actions were performed against the target application.


## Author

Devisha Bhatia
Cyber Security Intern - Future Interns
