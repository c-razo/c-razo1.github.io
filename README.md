# Chris Razo
**Dedicated IT & Cybersecurity Professional**

## About Me:
I am a cybersecurity professional certified in ISC2 Certified in Cybersecurity, CompTIA Security+, and Coursera Cybersecurity.

## Certifications:
- **CompTIA Security+**: [View](CompTIA-Security-Plus-Certificate.pdf)
- **ISC2 Certified in Cybersecurity**: [View](ISC2-CC-Certification.pdf)
- **Coursera Cybersecurity Certificate**: [View](Google-Cybersecurity-Certificate.pdf)

## Contact:
- **Email**: christopher.razo@icloud.com
- **LinkedIn**: [Visit](https://linkedin.com/in/christopher-razo)
- **Resume**: [View](/CR-Resume.pdf)


## Skills & Tools:

Here are some of the tools I’ve worked with in cybersecurity:

- **MacBook Pro**: Apple M3Pro, 18 GB, MacOS Sequoia Version 15.0.1.
- **Virtual Machine**: Kali Linux Debian 12.x 64-bit Arm via VMWare Fusion.
- **Wireshark**: Network analysis and packet inspection.
- **Burp Suite**: Web vulnerability scanning.
- **Metasploit**: Exploitation and security testing.
- **Nessus**:
- **John the Ripper**:
- **ChatGPT**:
- MariaDB Shell


## Projects and Labs:

### 1. Cybersecurity Checklist Project

**Description**:Strong Passwords, Multi-factor Authentication, Wi-Fi Protected Access 2 (WPA2), and everthing else a small business owner should focus on to maintain a strong, yet minimum security posture.

**Steps Taken**:

**Tools Used**:

**Outcome**:

[Details](blog-post1.md)


### 2. SSL/TLS Configuration Project

**Description**: - UPDATE TO INCLUDE DOWNLOADING NESSUS - This project was initiated after a Nessus scan identified an SSL certificate trust issue on a local Apache server. The scan result prompted a hands-on project to set up HTTPS using a self-signed SSL certificate on Apache.

**Steps Taken**:
- Used OpenSSL to generate a self-signed certificate and configure Apache for HTTPS.
- Updated Apache settings to listen on port 443 and configured SSL.
- Tested the setup by accessing `https://localhost` and documented the browser’s security warning.

**Tools Used**: Nessus, OpenSSL, Apache

**Outcome**: Successfully configured Apache to use HTTPS, demonstrating basic SSL/TLS setup and encryption, despite the self-signed certificate warning.

[Details](ssl-tls-apache-setup.md)


### 3. Password Cracking & Encryption Project

**Description**: This project focused on understanding password security by exploring password-cracking techniques with John the Ripper and Hashcat. The goal was to create and crack a sample hashed password, simulating a real-world scenario where weak passwords can be exposed. During the process, limitations were encountered due to system resource constraints, offering insight into the hardware requirements for intensive cryptographic tasks.

**Steps Taken**:
- Set up a Kali Linux Debian VM on VMware Fusion with 2 CPU cores and 20 GB storage.
- Installed John the Ripper and Hashcat to test password-cracking capabilities.
- Generated a SHA-512 hashed password using OpenSSL and saved it in a file.
- Used John the Ripper to crack the password, documenting the successful results.
- Attempted to use Hashcat for cracking, but adjusted settings after encountering memory limitations on the VM.

**Tools Used**: John the Ripper, Hashcat, OpenSSL, VMware Fusion

**Outcome**: Successfully demonstrated the process of creating and cracking a hashed password, emphasizing the importance of strong password practices and the role of hardware capabilities in security testing.

[Details](2024-11-04-password-cracking.md)


### 4. SQL Filtering Lab

**Description**: In this lab, I practiced using SQL queries to retrieve specific data from a database. The lab focused on filtering data using `AND`, `OR`, and `NOT` operators.

**Steps Taken**:

**Tools Used**: Kali Linux VM, MariaDB Shell, ChatGPT

**Outcome**: This SQL Filtering Lab demonstrates my ability to apply essential data creation and retrieval techniques, as well as adaptational learning combining virtual machines and AI tools, both crucial for cybersecurity analysis in the 2024 digital landscape and beyond.

[Details](2024-11-05-sql-filtering-lab.md)


### 5. Network Analysis Lab

**Description**: This project involved using Wireshark to capture and analyze network traffic, focusing on identifying potential indicators of suspicious activity. The goal was to gain practical experience with network analysis by examining packet details, IP addresses, timing, and patterns in data transmission.

**Steps Taken**:
- Installed Wireshark and configured it to capture live network traffic on the MacBook Pro.
- Filtered traffic to isolate packets with PSH, ACK flags, which can sometimes indicate data transfer or potential exfiltration.
- Reviewed unfamiliar IP addresses using VirusTotal to check for any known malicious associations.
- Analyzed timing patterns of repeated PSH, ACK packets to determine if there was evidence of automated or suspicious behavior.

**Tools Used**: Wireshark, VirusTotal

**Outcome**: Successfully identified and documented a methodology for filtering and analyzing network traffic for suspicious indicators. No malicious activity was detected during the analysis, but potential vulnerabilities were noted, including outdated TLSv1.1 traffic and connections to unfamiliar IP addresses, which could suggest further investigation in a production environment.

**Additional Analysis Steps**:

Capture Traffic Over Time: Monitor traffic at different times of day or during high-usage periods to see if any patterns change, especially with unfamiliar IPs.
Deep Packet Inspection: Investigate the content of other flagged packets more closely, as some patterns may not appear suspicious without examining multiple data points over time.
Compare Against Known Good Baseline: Regularly analyze and document known good traffic to better identify anomalies, especially in a business or production environment.

[Details](network-analysis-lab.md)


## Blog/Articles:

## Case Studies:

### Simulated Phishing Attack
- **Scenario**: Simulated a phishing attack to understand common tactics and identify red flags.
- **Outcome**: Gained insights into recognizing phishing emails and implementing best practices for avoiding them.

### Incident Response Walkthrough
- **Scenario**: Practiced a simulated incident response for a malware infection.
- **Outcome**: Learned the steps for identifying, containing, and eradicating threats.

## Code Samples:

- [Python Scripts for Network Security](https://github.com/yourusername/repo-name): Python scripts for network monitoring and analysis.
- [PowerShell Security Scripts](https://github.com/yourusername/repo-name): PowerShell scripts for Windows system security.
