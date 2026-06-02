# PTES Penetration Test Report - Week 3

## 1. Executive Summary
Multiple critical vulnerabilities were discovered during testing of a vulnerable environment. These include SQL Injection, XSS, and outdated services that expose the system to unauthorized access.

## 2. Methodology
- Reconnaissance using Nmap
- Exploitation using Metasploit
- Web testing using DVWA
- Traffic analysis using Burp Suite

## 3. Key Findings
- SQL Injection (Critical)
- Reflected XSS (Medium)
- FTP Backdoor (Critical)
- Outdated Apache & SSH Services (High)

## 4. Recommendations
- Use parameterized queries
- Update all outdated services
- Disable anonymous FTP access
- Implement input validation and output encoding
- Use WAF protection

## 5. Conclusion
The system contains multiple high-risk vulnerabilities that could be exploited to gain unauthorized access and compromise sensitive data.
