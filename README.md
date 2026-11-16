# Metasploitable Brute Force Attack Lab

\<p align="center">   \<b>Practical Cybersecurity | Authentication Security Testing\</b> \</p>

## Project Overview

This repository contains a practical cybersecurity lab focused on performing authorized Brute Force Attack testing against the Metasploitable vulnerable virtual machine.

The project demonstrates authentication security testing using the Metasploit Framework and Burp Suite in an isolated lab environment.

The objective is to understand password security weaknesses, authentication vulnerabilities, and the importance of implementing strong security controls.

## Objectives

- Understand the concept of Brute Force Attacks.
- Perform authentication security testing in a controlled lab.
- Explore the capabilities of Metasploit Framework.
- Understand Burp Suite and its Intruder functionality.
- Identify weak authentication practices.
- Analyze testing results and security implications.
- Recommend effective protection mechanisms.

## Lab Environment

| Component           | Details                             |
| ------------------- | ----------------------------------- |
| Attacker Machine    | Kali Linux                          |
| Target Machine      | Metasploitable                      |
| Virtualization      | VirtualBox / VMware                 |
| Testing Environment | Isolated Virtual Lab                |
| Operating System    | Linux                               |
| Project Type        | Educational Penetration Testing Lab |

## Tools & Technologies

| Tool                         | Purpose                                 |
| ---------------------------- | --------------------------------------- |
| Kali Linux                   | Penetration Testing Environment         |
| Metasploit Framework         | Authentication Security Testing         |
| Burp Suite Community Edition | Web Application Security Testing        |
| Metasploitable               | Intentionally Vulnerable Target Machine |
| VirtualBox / VMware          | Virtual Lab Environment                 |

## Attack Categories

The assignment provides the following protocol options:

- **FTP:** File Transfer Protocol Authentication Testing
- **Telnet:** Remote Login Authentication Testing
- **SSH:** Secure Shell Authentication Testing
- **HTTP:** Web Login Authentication Testing

## Repository Structure

```text
metasploitable-brute-force-lab/
│
├── README.md
│
├── Report/
│   └── Brute_Force_Attack_Report.pdf
│
├── Screenshots/
│   ├── 01-lab-setup.png
│   ├── 02-target-discovery.png
│   ├── 03-tool-configuration.png
│   ├── 04-testing-execution.png
│   ├── 05-authentication-result.png
│   └── 06-security-analysis.png
│
└── Notes/
    └── methodology.md
```

## Methodology

The practical assessment follows these general phases:

1. Lab Environment Setup
2. Target Machine Discovery
3. Service Identification
4. Tool Configuration
5. Controlled Authentication Testing
6. Result Observation
7. Evidence Collection
8. Security Analysis
9. Recommendations

## Screenshots & Evidence

Practical screenshots and supporting evidence will be organized in the `Screenshots/` directory.

Each screenshot will include a short description explaining the testing stage, observations, and relevant results.

## Findings

The findings section documents the observations obtained during the practical assessment.

It may include:

- Authentication weaknesses.
- Password security observations.
- Service configuration issues.
- Successful or unsuccessful authentication attempts.
- Potential security risks.

Only verified results from the lab assessment will be documented.

## Security Recommendations

- Use strong and unique passwords.
- Implement account lockout policies.
- Apply rate limiting to authentication endpoints.
- Enable Multi-Factor Authentication (MFA).
- Disable unnecessary services.
- Prefer encrypted protocols over insecure alternatives.
- Monitor authentication logs for suspicious activities.
- Regularly assess authentication security.

## Learning Outcomes

Through this practical lab, the project aims to develop an understanding of:

- Authentication Security
- Password Security
- Brute Force Attack Concepts
- Metasploit Framework
- Burp Suite Intruder
- Vulnerability Assessment
- Security Analysis and Reporting

## Author

**Sheikh Sabbir Hossain**

Cybersecurity Enthusiast | Web Security | VAPT | Penetration Testing | Bug Bounty Hunting | AI & LLM Security

- GitHub: [@sabbihossen](https://github.com/sabbihossen)
- LinkedIn: [Sheikh Sabbir Hossain](https://linkedin.com/in/sheikh-sabbir-hossain-661157368/)

## Disclaimer

This project is intended strictly for educational purposes and authorized security testing within an isolated lab environment.

The techniques discussed must only be used on systems for which explicit permission has been granted.

**Unauthorized access or testing against third-party systems is strictly prohibited.**

---

\<p align="center">
&#x20; \<b>Learn • Practice • Analyze • Secure\</b>
\</p>
