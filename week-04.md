# 🛡️ Week 4 – Cybersecurity Notes

---

## 👤 Identity & Access Management (IAM)

IAM focuses on managing digital identities and regulating access to systems and resources using the 4 A's:

- **Administration (Admin)** – Identity provisioning and deprovisioning  
- **Authentication (Authn)** – Confirms **who** the user is  
- **Authorization (Authz)** – Determines what the user is **allowed** to do  
- **Audit** – Tracks access and changes for accountability and compliance  

---

## 🔐 Access Control Models & Permissions

- Access control ensures only **authorized** users access specific data or systems  
- Identity = unique digital representation of a user, device, or application  
- Access control models include:
  - **RBAC** – Role-Based Access Control
  - **ABAC** – Attribute-Based Access Control
  - **MAC** – Mandatory Access Control
  - **DAC** – Discretionary Access Control
  - **RuBAC** – Rule-Based Access Control
- File access control in Linux/Windows highlights the need for **precise permissions**  
- Two main types of access control:
  - **Traditional** – (MAC, DAC, RBAC)
  - **Innovative** – (ABAC, risk/context-based)

---

## 🔑 Authentication Methods

- Authentication verifies a user’s claimed identity  
- Common authentication protocols:
  - **RADIUS**, **CHAP**, **EAP**, **Kerberos**  
- Authentication servers (e.g., **Active Directory**, **LDAP**, **RADIUS**) store credentials  
- Passwords are vulnerable (can be guessed, stolen, reused)  
- Additional authentication methods:
  - **OTP (One-Time Password)**
  - **Biometric Authentication**
  - **Smart Cards**
  - **Security Tokens**
  - **Mobile Push Notifications**

---

## 🔐 MFA, SSO & Password Management

- **MFA (Multi-Factor Authentication)**: Adds extra security by requiring multiple methods of verification  
- **SSO (Single Sign-On)**: Lets users log in once to access multiple systems  
  - Benefits: Better **security**, lower **cost**, improved **UX**  
- Password management concerns:
  - Lost or forgotten passwords
  - Using multiple devices
  - Phishing attacks targeting credentials  
- Solutions:
  - **Password managers**
  - Strong password hygiene: **complex**, **unique**, **fresh**

---

## 🌍 Physical & Environmental Security

- Physical threats affect cybersecurity too  
- Examples:
  - Unauthorized physical access
  - Theft of devices
  - Environmental events: **floods, fires, earthquakes**  
- Security strategies:
  - Surveillance, restricted access, alarms
  - Outdoor perimeter security  
- Goal: Maintain **data security** and ensure **operational continuity**

---
📘 **Disclaimer**: These notes are based on the IBM course *"Introduction to Cybersecurity Tools & Cyberattacks"* on [Coursera](https://www.coursera.org/learn/introduction-cybersecurity-cyber-attacks#modules).  
They are written for **personal learning and educational use only**.
