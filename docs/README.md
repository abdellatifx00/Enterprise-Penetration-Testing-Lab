
# Technical Documentation

This directory contains detailed documentation covering the lab architecture, environment setup, penetration testing methodology, findings, and remediation recommendations.

## Network Architecture

The lab uses pfSense to connect and control traffic between three network segments.

```mermaid
flowchart TB
    K["Kali Linux<br/>Penetration Testing<br/>10.10.20.50"]
    FW["pfSense Firewall"]
    WEB["Ubuntu Server<br/>OWASP Juice Shop<br/>10.10.30.10"]
    DC["Windows Server 2022<br/>Internal Network"]
    CLIENT["Windows 10 Client<br/>Internal Network"]

    K ---|"Pentest LAN<br/>10.10.20.0/24"| FW
    FW ---|"Web LAN / DMZ<br/>10.10.30.0/24"| WEB
    FW ---|"Internal LAN<br/>10.10.10.0/24"| DC
    DC --- CLIENT
```

**Important:** This diagram represents the intended logical architecture. Firewall enforcement, domain configuration, and connectivity must be independently validated before treating the diagram as proof of those controls.
