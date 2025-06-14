# 🛡️ Week 3 – Cybersecurity Notes

---

## 🔍 Network Mapping & Monitoring

- **Network Mapping**: Visualizes physical and logical structure of a network.
- **Nmap**: Popular tool to:
  - Identify active devices
  - Discover open ports
  - Detect security risks
- **Wireshark**: Protocol analyzer used to:
  - Capture network traffic
  - Analyze specific packet-level details
- Benefits of mapping:
  - Manage network complexity
  - Troubleshoot issues
  - Detect anomalies

---

## 📡 Packet Sniffing & Threats

- **Packet Sniffing**: Captures and inspects data packets on a network.
- Used by:
  - **IT Teams** – for monitoring and troubleshooting
  - **Attackers** – to steal login credentials, personal info, etc.
- Two types:
  - **Passive sniffing** – eavesdropping
  - **Active sniffing** – interacts with traffic
- **Defense strategies**:
  - System updates
  - Strong login practices
  - Email hygiene
  - VPNs and HTTPS

---

## 🗺️ Attacker Use of Network Mapping

Attackers use mapping to:
- Identify:
  - Unguarded entry points
  - Vulnerable systems
  - Defense mechanisms
- Navigate networks
- Prioritize target segments
- Deduce high-value assets
- Launch phishing or social engineering campaigns

---

## 🔀 IP Spoofing, Botnets & MITM

- **IP Spoofing**: Alters packet headers to disguise the source.
- Used in:
  - **DDoS attacks**
  - **Botnets**: Networks of infected computers
  - **Man-in-the-middle attacks**
- Challenges:
  - Difficult for law enforcement to trace
- Defenses:
  - **Ingress filtering**
  - **Egress filtering**

---

## 🔐 Security Controls & CIA Triad

- Controls protect:
  - **Confidentiality**
  - **Integrity**
  - **Availability**
- Types of controls:
  - **Administrative**
  - **Physical**
  - **Technical**
- Categories:
  - **Deterrent**
  - **Preventive**
  - **Detective**
  - **Corrective**
- Examples:
  - Patching, Redundancy, Monitoring (SIEM/XDR), SOAR, Filtering

---

## 💉 Injection Attacks: SQLi & XSS

- **Injection attacks** insert malicious code into websites/apps.
- Common types:
  - **SQL injection** – targets databases
  - **XSS (Cross-site scripting)**:
    - **Server XSS**
    - **Client XSS**
- Purpose: Gain unauthorized access to sensitive data

---

## 💻 System & Application Security

- **System security** includes hardware & software protections.
- Key techniques:
  - Access controls
  - Encryption
  - Patching
  - Backups
  - Firewalls & antivirus
- **Application security** includes:
  - Input validation
  - Error handling
  - Secure logging
  - Avoid hardcoded credentials
  - Secure access control & encryption

---

## 🌐 Network Security Basics

- Goals:
  - Prevent unauthorized access
  - Identify/stop cyber threats
  - Ensure legitimate access for users
- Tools used:
  - Firewalls, NACs, IDPS
  - VPNs, SIEM, SOAR
  - Endpoint security
  - Network segmentation

---

## 🧪 Vulnerability Management

- Step 1: Define scan targets
- Perform **automated scans** regularly
- Use tools like:
  - **Nessus**
  - **OpenVAS**
- Test methods:
  - **SAST** – Static Analysis
  - **DAST** – Dynamic Analysis
  - **IAST** – Interactive Analysis
- Important: Tune parameters to detect deep vulnerabilities

---

## 🚨 Incident Response & Digital Forensics

- IR strategy includes:
  1. **Preparation & Planning**
  2. **Detection & Analysis**
  3. **Containment, Eradication, Recovery**
  4. **Post-Incident Activities**
- **Digital Forensics**: Recover, preserve, and document digital evidence for analysis.

---
