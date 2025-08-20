# OpenEMR Penetration Testing & HIPAA Security Report

This project involved conducting a **penetration test on OpenEMR**, a healthcare electronic medical record (EMR) system, in a controlled virtual lab environment.  
The assessment simulated real-world attack vectors while aligning with **HIPAA Security Rule compliance requirements**.

---

## 🔹 Project Overview
- **Environment:** Oracle VirtualBox with Ubuntu (hosting OpenEMR + MySQL) and Kali Linux (attacker).  
- **Objective:** Identify vulnerabilities in OpenEMR, exploit them, and map security gaps against HIPAA requirements.  

---

## 🔹 Methodology
1. **Information Gathering** – Service enumeration with Nmap & directory discovery with Gobuster.  
2. **Vulnerability Analysis** – Identified weak authentication and outdated OpenEMR version.  
3. **Exploitation** – Used Hydra, SQL Injection techniques, and Metasploit modules.  
4. **Post-Exploitation** – Extracted credentials, enumerated system users, and reviewed patient database records.  
5. **HIPAA Mapping** – Assessed risks against HIPAA safeguards for confidentiality, integrity, and availability of PHI.  

---

## 🔹 Key Findings
- **Weak MySQL Authentication:** Default/guessable credentials.  
- **Unpatched OpenEMR Version:** Exposed to known vulnerabilities.  
- **Sensitive Data Exposure:** PHI stored unencrypted.  
- **Directory Enumeration:** Hidden admin panels exposed.  

---

## 🔹 Recommendations
- Enforce **strong password policies** and enable MFA.  
- Upgrade OpenEMR to the **latest patched version**.  
- Encrypt PHI at rest and enforce TLS-based connections.  
- Harden Apache configuration and restrict directory access.  
- Implement intrusion detection & continuous security monitoring.  

---

## 🔹 Skills Demonstrated
- Penetration Testing (Nmap, Hydra, Gobuster, Metasploit)  
- Healthcare Cybersecurity (EMR Security, HIPAA Compliance)  
- Risk Assessment & Vulnerability Management  
- Database Security & Access Control  
- Compliance Reporting  

---

## 📄 Report
The full penetration test and HIPAA impact report (with evidence & screenshots) is included in this repository.  

**Author:** Faris Ali  
