# ApexPlanet Task 5 – Capstone Project & Incident Response

## Cybersecurity & Ethical Hacking Internship

This repository contains the work completed for **Task 5: Capstone Project & Incident Response** as part of the **ApexPlanet Cybersecurity & Ethical Hacking Internship**.

The project combines a controlled **Web Application Penetration Testing assessment** with an **Incident Response simulation** using an intentionally vulnerable web application in an isolated virtual laboratory environment.

---

##  Project Overview

The capstone project focuses on identifying, exploiting, analyzing, and mitigating web application security vulnerabilities in **Damn Vulnerable Web Application (DVWA)**.

The primary security scenario investigated in this project is:

> **SQL Injection (SQLi)**

The project also documents supporting web application security testing scenarios including:

- Stored Cross-Site Scripting (XSS)
- Reflected Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)

Following the controlled exploitation phase, an incident response simulation was performed using Apache web server logs to identify and analyze the recorded attack activity.

---

## Objectives

The main objectives of this capstone project are:

- Perform reconnaissance and service enumeration.
- Assess a vulnerable web application for security weaknesses.
- Demonstrate SQL Injection in a controlled environment.
- Analyze vulnerable application source code.
- Examine web server logs associated with attack activity.
- Simulate an incident response workflow.
- Demonstrate containment, eradication, recovery, and verification.
- Identify the root cause of the vulnerability.
- Document appropriate mitigation and security recommendations.
- Prepare a professional capstone report and demonstration.

---

##  Laboratory Environment

The project was conducted within an isolated virtual laboratory environment.

### Environment Components

| Component | Purpose |
|---|---|
| Kali Linux | Security testing and analysis workstation |
| DVWA | Intentionally vulnerable web application |
| Apache | Web server |
| MariaDB/MySQL | Database service |
| VirtualBox | Virtualization platform |
| Nmap | Reconnaissance and service enumeration |
| Burp Suite Community Edition | Web application testing |
| Apache Access Logs | Incident detection and analysis |

All testing was performed against intentionally vulnerable systems within an authorized laboratory environment.

---

## Primary Security Scenario

### SQL Injection

SQL Injection was selected as the primary vulnerability for the capstone incident-response scenario.

The assessment included:

1. Establishing a normal application baseline.
2. Performing controlled SQL Injection testing.
3. Observing the application's response.
4. Demonstrating unauthorized database information retrieval.
5. Reviewing the vulnerable application source code.
6. Identifying the root cause.
7. Analyzing Apache access logs.
8. Correlating HTTP requests with observed application behavior.
9. Applying the protected application configuration.
10. Performing recovery and verification testing.

---

## 🚨 Incident Response Simulation

The incident response portion follows a structured workflow:

```text
Detection
   ↓
Analysis
   ↓
Containment
   ↓
Eradication
   ↓
Recovery
   ↓
Verification

Detection

Apache access logs were examined to identify requests associated with the simulated SQL Injection activity.

Analysis

The recorded HTTP requests were correlated with:

Observed DVWA behavior
SQL Injection testing results
Vulnerable application source code
Containment

The vulnerable testing configuration was removed from the active scenario and the protected DVWA configuration was applied.

Eradication

The vulnerable SQL query construction was replaced with a protected implementation using prepared statements and parameter binding.

Recovery

The application was returned to the protected configuration and the SQL Injection scenario was retested.

Verification

The same testing scenario was performed against the protected configuration to verify that the previously observed unauthorized database output was not reproduced.

Key Security Concepts Demonstrated

This project demonstrates practical understanding of:

Reconnaissance
Service enumeration
Web application penetration testing
SQL Injection
Cross-Site Scripting
CSRF
Source code analysis
HTTP request analysis
Apache log analysis
Incident detection
Incident response
Root cause analysis
Vulnerability mitigation
Prepared statements
Security verification
Security documentation

🛡️ Security & Ethical Considerations

This project was performed strictly within an authorized and isolated cybersecurity laboratory environment.

The vulnerable applications and systems used in this project are intended for security education and controlled testing.

No unauthorized external systems were targeted.

Sensitive information such as real credentials, private keys, session tokens, API keys, or personal information is not intentionally included in this repository.

Final Deliverables

The completed capstone project includes:

Project planning documentation
Reconnaissance documentation
Vulnerability assessment
Controlled SQL Injection demonstration
Incident response simulation
Evidence documentation
Network architecture diagram
Security mitigation recommendations
Final capstone report
Demonstration video
 Internship

Program: Cybersecurity & Ethical Hacking Internship
Organization: ApexPlanet
Task: Task 5 – Capstone Project & Incident Response

isclaimer

This repository is intended for educational and authorized cybersecurity testing purposes only.

The techniques and tools demonstrated here should only be used against systems for which explicit authorization has been obtained.
