
# Project Status

## Completed

- [x] Designed the virtual network architecture.
- [x] Deployed pfSense and configured the lab network interfaces.
- [x] Established the Windows Server and Windows client lab environment.
- [x] Created project documentation and a network topology diagram.

## In Progress

- [ ] Complete and validate the Ubuntu web server deployment.
- [ ] Deploy and verify OWASP Juice Shop.
- [ ] Validate network connectivity and firewall segmentation.

## Phase 1: Web Application Penetration Testing

**Objective:** Assess the exposed web application and investigate whether a vulnerability could provide an initial foothold on the web server.

- [ ] Perform reconnaissance and service enumeration.
- [ ] Identify and validate web application vulnerabilities.
- [ ] Conduct controlled exploitation within the lab.
- [ ] Assess the access and privileges obtained.
- [ ] Document findings, impact, and remediation.

## Phase 2: Internal Network Pivoting & Active Directory Assessment

**Objective:** Starting from the web server foothold, assess whether the network architecture or security misconfigurations could allow access to internal systems, then evaluate the security of the Active Directory environment.

- [ ] Assess connectivity and access from the web server to internal network segments.
- [ ] Enumerate reachable internal hosts and services.
- [ ] Evaluate potential pivoting and lateral movement paths.
- [ ] Assess Active Directory security, domain configurations, and privilege relationships.
- [ ] Investigate privilege escalation opportunities within the authorized lab.
- [ ] Document attack paths, potential impact, and remediation recommendations.

## Final Deliverables

- [ ] Document the methodology and evidence for both phases.
- [ ] Produce a technical report with validated findings and remediation guidance.
- [ ] Update the network architecture and project documentation based on test results.

## Update Policy

Tasks will be marked complete only after implementation or testing has been verified. Potential attack paths will be distinguished from successfully demonstrated ones.
