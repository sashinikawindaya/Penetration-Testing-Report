# Penetration Testing Report – Clarke’s Ceylon

## 📌 Overview

This project presents a comprehensive **penetration testing report** conducted on **Clarke’s Ceylon Team**, a Sri Lankan tea manufacturer undergoing digital transformation. The testing was performed as part of the **Ethical Hacking (PUSL3132)** coursework for the **BSc (Hons) in Computer Security** program.

The primary objective was to identify and mitigate vulnerabilities across the organization's digital infrastructure, focusing on live systems due to the absence of a test environment. Our team applied both **manual and automated techniques** to simulate real-world cyberattacks responsibly and ethically.

---

## 🛠 Scope of Work

The following areas were tested:

- **Network Security:** Open ports, segmentation, and firewall configuration.
- **Application Security:** Desktop and web application vulnerabilities.
- **Organizational Security:** Staff awareness, policy evaluation, and compliance.

---

## 🧪 Methodology

We employed a combination of industry-standard tools and frameworks, including:

- **Nmap** – Network discovery and port scanning.
- **Nessus Essentials** – Vulnerability assessment.
- **Metasploit Framework** – Exploitation (e.g., EternalBlue MS17-010).
- **John the Ripper** – Password hash cracking.

Each test was carefully documented with screenshots and technical analysis.

---

## 🛡 Key Findings & Exploits

Some of the major vulnerabilities identified include:

- Unpatched systems (e.g., Windows Server 2008 R2, Windows 7)
- Critical SMB vulnerabilities (MS17-010 - EternalBlue)
- Outdated SSL/TLS configurations
- Weak or self-signed SSL certificates
- Telnet services transmitting unencrypted credentials
- Lack of SMB signing and NLA for RDP

---

## 🔧 Mitigation Recommendations

To secure the environment, we recommend:

- Upgrading unsupported OS versions.
- Disabling legacy protocols like SMBv1 and TLS 1.0/1.1.
- Enforcing SMB signing and enabling NLA.
- Replacing self-signed certificates with CA-issued SSL certs.
- Using SSH instead of Telnet.

Detailed recommendations for each host are provided in the full report.

---

## 📄 Report Content

The repository includes the full PDF report:

- **Introduction**
- **Background & Legal Considerations**
- **Testing Methodology**
- **Evaluation of Results**
- **Mitigation Strategies**
- **Conclusion**
- **References**

---

## 👨‍💻 Authors (Group 37)

- **Polwaththage D Kawindaya** – Introduction & Background  
- **Wickrama Wickramaarachchi** – Testing Methodology, Conclusion & Evaluation  
- **Siyabalapitiyage Madushanka** – Evaluation  
- **Basnayaka Basnayaka** – Mitigation  

---

## 🔒 Disclaimer

This project was carried out under the academic supervision of Plymouth University and follows ethical guidelines for penetration testing. All tests were conducted with prior authorization, and no unauthorized systems were affected.

---

## 📚 References

- Nessus Vulnerability Plugin Resources  
- Microsoft Security Advisory Portal  
- Metasploit Exploit Database  
- EternalRocks GitHub Repo  
- Badlock Vulnerability Disclosure  

---
