# CTF-Agent-T-THM
php vulnerability explotation RCE

## Objective
The objective of the Agent T CTF room is to simulate a realistic penetration test where you investigate a suspicious web service, identify vulnerabilities, and exploit them to gain unauthorized access. The core challenge revolves around discovering that the server is running an exposed and vulnerable version of PHP/8.1.0-dev, which includes a debug interface on port 8080 that allows unauthenticated remote code execution (RCE). Your goal is to leverage this misconfiguration to execute commands, explore the system, and ultimately locate and capture the hidden flag. This CTF teaches critical skills like service enumeration, exploitation of insecure development environments, and post-exploitation enumeration—all of which are foundational for real-world cybersecurity work.

### Skills Learned
### Reconnaissance and Enumeration
- Identified technologies and software versions (e.g. PHP/8.1.0-dev)
- Scanned for open ports and exposed services (e.g. port 8080)

### Exploitation Techniques
- Exploited an exposed PHP debug interface for unauthenticated remote code execution (RCE)
- Crafted and delivered PHP payloads using tools like `netcat`

### Understanding Misconfigurations
- Recognized the risks of using development builds in production environments
- Identified default services or features that should be disabled

### Post-Exploitation
- Navigated the file system after gaining shell access
- Searched for and retrieved sensitive data (e.g. flag files)

### Hands-on Practice with Tools
- Used tools like `nmap`, `curl`, and `nc` in real-world scenarios

### Real-world Cybersecurity Concepts
- Gained a practical understanding of RCE vulnerabilities
- Learned how misconfigured systems can lead to full compromise

### Tools Used
[Bullet Points - Remove this afterwards]

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*
