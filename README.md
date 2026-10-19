
# Enterprise Network, Web Application & Active Directory Penetration Testing Lab

## Overview

This project focuses on building an integrated enterprise-style environment to practice penetration testing across web applications, network infrastructure, and Active Directory.

Using VirtualBox, pfSense, Windows Server, Windows client systems, Ubuntu Server, and OWASP Juice Shop, the lab is designed to simulate a realistic environment where different systems and security boundaries can be assessed together.

The objective is to understand how vulnerabilities and misconfigurations across multiple layers can affect an organization's security posture.

## Lab Architecture

The environment is designed around three main network segments:

- **Internal Network:** Windows Server and Windows client systems representing the enterprise environment.
- **Penetration Testing Network:** Kali Linux for reconnaissance, security assessment, and authorized testing.
- **Web Network / DMZ:** Ubuntu Server hosting OWASP Juice Shop as the web application testing target.

**pfSense** acts as the firewall between network segments, providing a foundation for evaluating network isolation and access controls.

> A network topology diagram will be added as the lab documentation develops.

## What Has Been Accomplished

### 1. Network Architecture

- Designed the virtual network architecture in VirtualBox.
- Established separate network segments for internal systems, penetration testing, and web services.
- Deployed pfSense and configured its network interfaces.
- Began establishing the foundation for controlled communication between network segments.

### 2. Enterprise Windows Environment

- Set up a Windows Server environment for Active Directory practice.
- Prepared a Windows client as part of the internal enterprise network.
- Worked on network connectivity between the Windows environment and the lab firewall.

### 3. Web Server and Application

- Set up an Ubuntu Server environment for hosting the web application.
- Installed and configured OWASP Juice Shop as the intentionally vulnerable testing target.
- Integrated the web application into the lab design to support realistic web-to-internal-network attack scenarios.

## Project Objectives

The lab is intended to explore how an assessment can progress from an exposed web application toward an enterprise network, while validating the security boundaries between systems.

Planned testing phases include:

1. **Reconnaissance:** Identify exposed services, accessible assets, and potential entry points.
2. **Enumeration:** Gather detailed information about discovered services and systems.
3. **Vulnerability Assessment:** Identify and validate potential security weaknesses.
4. **Exploitation:** Safely demonstrate vulnerabilities within the authorized lab.
5. **Post-Exploitation:** Assess the access obtained and its security implications.
6. **Privilege Escalation:** Investigate opportunities to obtain higher privileges.
7. **Lateral Movement:** Evaluate whether access to one system could enable access to other internal systems.
8. **Active Directory Assessment:** Investigate domain security, privilege relationships, misconfigurations, and potential attack paths.
9. **Reporting and Remediation:** Document evidence, assess impact, and recommend appropriate mitigations.

These phases will be documented as they are performed and validated.

## Technology Stack

- **Virtualization:** Oracle VirtualBox
- **Firewall:** pfSense
- **Penetration Testing OS:** Kali Linux
- **Server Environment:** Windows Server and Ubuntu Server
- **Client Environment:** Windows client
- **Web Application:** OWASP Juice Shop
- **Core Focus Areas:** Web Application Security, Network Penetration Testing, Active Directory Security

## Documentation and Progress

This repository will evolve throughout the project and include:

- Network architecture and topology diagrams
- Lab setup and configuration notes
- Screenshots and technical evidence
- Testing methodology and validated findings
- Risk analysis and remediation recommendations
- Progress updates for each assessment phase

## Disclaimer

This environment is intended for educational purposes and authorized security testing only.

Testing is conducted against systems within the controlled lab environment. Any techniques discussed are intended to support security validation, risk assessment, and defensive improvement.

## Project Status

**Status:** In Progress

The lab foundation is being developed, with upcoming work focused on validating the environment, conducting web application assessments, evaluating network boundaries, and progressing toward Active Directory penetration testing.
