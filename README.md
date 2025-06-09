# Task-3
Task 3 for Elevate Labs
# Task 3: Perform a Basic Vulnerability Scan on Your PC

## Objective

This task focuses on using a free vulnerability scanner to assess your system for potential security issues. The goal is to gain hands-on experience with scanning tools and understand how to identify, analyze, and prioritize vulnerabilities in personal computers.

---

## Key Concepts Covered

- Vulnerability Scanning
- Risk Assessment
- CVSS (Common Vulnerability Scoring System)
- False Positives
- Remediation and Mitigation Techniques
- Security Tools

---

## Tools Used

- OpenVAS Community Edition
- Localhost/PC IP Address
- CVSS Database (for vulnerability scoring references)

---

## Steps Followed

1. Installed OpenVAS Community Edition on the system.
2. Set up the scan target as `localhost` or the local IP address.
3. Performed a full vulnerability scan (scan duration: approx. 45 minutes).
4. Waited for scan to complete and exported the report.
5. Reviewed the vulnerabilities found and noted their CVSS scores.
6. Researched mitigation steps for high/critical severity vulnerabilities.
7. Documented the top issues and attached screenshots from the report.

---

## Vulnerability Scan Summary

| Vulnerability Title                 | Severity | CVSS Score | Description                              | Action Taken               |
|------------------------------------|----------|------------|------------------------------------------|----------------------------|
| Outdated OpenSSH Version Detected  | High     | 7.5        | May allow unauthorized access            | Updated to latest version |
| SMBv1 Enabled                      | Medium   | 6.0        | Legacy protocol vulnerable to exploits   | Disabled SMBv1             |
| Unused Port Open (TCP 111)         | Medium   | 5.8        | Can be exploited for RPC-related issues  | Port closed via firewall   |

