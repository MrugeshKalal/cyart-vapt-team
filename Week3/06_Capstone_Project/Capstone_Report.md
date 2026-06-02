# CAPSTONE VAPT REPORT

## 1. Introduction
This report summarizes a full penetration testing exercise performed on a vulnerable lab environment.

## 2. Methodology
- Reconnaissance using Nmap
- Exploitation using Metasploit
- Web testing using DVWA
- Traffic analysis using Burp Suite

## 3. Key Findings
- SQL Injection (Critical)
- XSS (Medium)
- FTP Backdoor (Critical)
- Outdated Services (High)

## 4. Impact
Attackers can gain unauthorized access, extract data, and execute remote commands.

## 5. Recommendations
- Patch all services
- Use input validation
- Disable anonymous FTP
- Implement WAF
- Regular vulnerability scanning

## 6. Conclusion
The environment contains multiple exploitable vulnerabilities and should not be exposed to production.

