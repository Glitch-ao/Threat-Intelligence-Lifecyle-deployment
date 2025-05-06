# Threat Intelligence & Gathering Concepts

This project focuses on identifying, collecting, and analyzing threat intelligence using various open-source intelligence (OSINT) tools, SIEM platforms, and endpoint log sources. I explored the use of OSINT tools for reconnaissance, implemented firewall and Windows event logging, and practiced incident response techniques using threat data and MITRE ATT&CK mappings.

## Tags
`OSINT` `Incident Response` `TTPs` `Windows Event Viewer` `Firewall Logging`

---

### 1. Open Source Intelligence (OSINT)
- Explored historical website data using **Wayback Machine (archive.org)** to identify outdated tech and potential exposure points.
- Used **Spiderfoot.net** and **BuiltWith.com** for passive surveillance and domain profiling (tech stack, subdomains, associations).
- Queried domain and personal data with **Intelx.io**, **whois.com**, and **website.informer.com**.
- Searched usernames and email addresses via **social-searcher.com** to gather public social presence and metadata.

### 2. Threat Hunting & Indicators of Compromise (IOCs)
- Identified and documented key IOCs:
  - Unusual network traffic
  - Privilege escalation attempts
  - Failed login attempts
  - Unusual IP addresses
  - DNS anomalies
  - System file/registry changes
  - Log clearing evidence
  - DDoS indicators

### 3. Incident Response & TTP Analysis
- Worked with a SIEM platform to simulate incident response scenarios.
- Collected and analyzed logs via **Windows Event Viewer**.
- Enabled and monitored **Windows Firewall Logging** to capture inbound/outbound traffic anomalies.
- Mapped attacker behavior using **MITRE ATT&CK** — categorized TTPs based on observed activity in log data.

### 4. Honeypot Tool
- Set up a lightweight honeypot environment to attract and log suspicious activity.
- Monitored unauthorized scans and exploit attempts.

---

## Learning Outcomes

By the end of this project, I was able to:

- Use multiple OSINT tools to gather threat intelligence from public sources
- Recognize and document common Indicators of Compromise (IOCs)
- Simulate and respond to basic security incidents using a SIEM
- Analyze logs from Windows Event Viewer
- Enable and review Windows Firewall Logs
- Identify adversarial behavior using MITRE ATT&CK's Tactics, Techniques, and Procedures (TTPs)
- Deploy a honeypot to collect unauthorized access attempts

---

## Tools & Platforms Used
- **Spiderfoot**, **BuiltWith**, **Wayback Machine**
- **Intelx.io**, **Whois.com**, **Website Informer**, **Social Searcher**
- **MITRE ATT&CK Framework**
- **Windows Event Viewer**, **Firewall Logging**
- **SIEM Platform (TryHackMe / Let'sDefend Labs)**
- **Custom Honeypot Simulation**

---

## Screenshots
*(Add screenshots of OSINT results, firewall log files, Windows Event logs, honeypot data, etc.)*

---

