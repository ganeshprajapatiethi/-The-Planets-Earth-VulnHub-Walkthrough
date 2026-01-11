# VulnHub: The Planets – Earth

## 🔐 Vulnerability
**Authenticated Command Injection leading to Privilege Escalation**

## 👤 Author
Ganesh Gourav – Cybersecurity Student

## 🎯 Target
- Machine: The Planets – Earth (VulnHub)
- IP: 192.168.29.149
- Environment: Local Lab (Educational Purpose)

## 🧪 Summary
The target machine was fully compromised by chaining multiple vulnerabilities:
- Network reconnaissance
- Web enumeration
- Weak XOR-based credential encryption
- Authenticated command injection
- Insecure SUID binary abuse

This resulted in full root-level system compromise.

## 🛠️ Attack Chain
1. Bettercap network discovery
2. Nmap service enumeration
3. Virtual host discovery
4. Credential recovery via XOR decryption
5. Command injection through admin panel
6. Privilege escalation via SUID binary

## 📄 Proof of Concept
👉 [Download Full POC Report (PDF)](https://drive.google.com/file/d/1a_2WeiUn_aYkvEsgb7MOc1FgvsztrvNF/view?usp=sharing)

## 🧯 Impact
- Arbitrary command execution
- Credential compromise
- Root privilege escalation
- Complete system takeover

## 🔧 Mitigation
- Remove unnecessary SUID binaries
- Disable command execution features
- Use strong cryptography
- Apply least privilege principle

## ⚠️ Disclaimer
This project is for **educational and ethical hacking practice only**.  
No real-world systems were targeted.
