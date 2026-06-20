# Vulnerability Assessment Report – OWASP Juice Shop

## Objective

Conduct a passive vulnerability assessment of the OWASP Juice Shop demonstration application to identify common web application security weaknesses.

## Target Application

**Website:** https://demo.owasp-juice.shop/#/

## Scope

This assessment was limited to passive security testing only.

### Allowed Activities

- Network reconnaissance using Nmap
- Service detection and version identification
- OWASP ZAP passive web application scanning
- HTTP security header analysis
- Browser-based inspection

### Activities Not Performed

- Exploitation of identified vulnerabilities
- Authentication bypass attempts
- Brute-force attacks
- Denial-of-Service (DoS) testing
- Modification of application data

## Tools Used

- Kali Linux 2025.2 (VMware)
- Nmap 7.95
- OWASP ZAP 2.17.0
- Firefox Developer Tools
- Git & GitHub

## Methodology

1. Performed network reconnaissance using Nmap.
2. Identified exposed services and technologies.
3. Conducted passive vulnerability analysis using OWASP ZAP.
4. Reviewed HTTP responses and security configurations.
5. Documented identified findings with evidence and remediation recommendations.

## Risk Summary

|  Risk Level   | Number of Findings |
|---------------|--------------------|
|    Medium     |         6          |
|     Low       |         5          |
| Informational |         4          |
|     High      |         0          |
|   **Total**   |      **15**        |
|---------------|--------------------|

## Key Findings

### Medium Risk
- Content Security Policy (CSP) Header Not Set
- Cross-Domain Misconfiguration (CORS)
- Missing Anti-Clickjacking Protection
- Session Identifier Exposure in URL
- Application Error Disclosure

### Low Risk
- Strict-Transport-Security (HSTS) Header Not Set
- X-Content-Type-Options Header Missing
- Debug Error Message Disclosure
- Private IP Disclosure
- Unix Timestamp Disclosure

### Informational Findings
- Authentication Request Identified
- Suspicious Comments Detected
- Cache-Control Directives Require Review
- Modern Web Application Identified

## Repository Structure

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
