# Ethical-hacking-journey
Offensive security 
To outsmart a hacker, you need to think like one."

This is the core of "Offensive Security." It involves breaking into computer systems, exploiting software bugs, and finding loopholes in applications to gain unauthorized access. The goal is to understand hacker tactics and get where they wanna be before them 
TryHackMe — Hacking a Simulated Bank

This is my write‑up from a TryHackMe offensive security lab where I practiced hacking a simulated bank website in a safe, legal environment.

⸻

🔍 1. Discovering Hidden Pages (DIRB)

I learned how to use DIRB to brute‑force hidden URLs on a website.
DIRB tries thousands of possible pages and reveals ones that are not visible to normal users.
command used 
dirb http://<target-ip>
DIRB discovered hidden pages like /admin and /transfers, which were the key to accessing the bank’s internal system.
Accessing the Admin Panel

TryHackMe showed how weak login pages can be exploited.
I found the admin page using DIRB and accessed it with default credentials provided in the simulation.



💸 3. Modifying Balances (Simulation Only)

Inside the simulated bank panel, the lab taught how insecure systems can allow attackers to change account values.
I followed the instructions and successfully added money to a test account — all part of the controlled learning environment.



🧠 What I Learned
		How directory brute forcing works
	How hidden URLs expose sensitive areas
	Basics of web exploitation
	Why proper authentication and security controls matter



📌 Summary

This was my first hands‑on offensive security experience, and it helped me understand how attackers think and how vulnerabilities can be discovered using tools like DIRB.

Defensive security /SOC track 
Defensive Security & SOC Fundamentals – TryHackMe Learning Summary

Over the past days, I completed the Defensive Security section on TryHackMe, focusing heavily on SOC (Security Operations Center) workflows and real‑world defensive techniques.
This track helped me build a strong understanding of how attackers operate and how defenders detect, analyze, and stop security threats.

🔍 What I Learned

1. Security Operations Center (SOC) Structure
	•	Roles inside a SOC (Tier 1, Tier 2, Tier 3 analysts, Incident Responders, Threat Hunters).
	•	How SOC teams monitor, investigate, and escalate alerts.
	•	Understanding SLAs, escalation paths, and incident severity levels.

2. Log Analysis & Monitoring
	•	Working with logs from:
	•	Windows Event Viewer
	•	Linux system logs
	•	Firewall and IDS/IPS
	•	Web servers (Apache, NGINX)
	•	Identifying malicious patterns such as failed RDP attempts, privilege escalation, or suspicious processes.

3. SIEM (Security Information and Event Management)
	•	How SIEM tools ingest, normalize, and correlate logs.
	•	Writing and understanding detection rules.
	•	Investigating alerts using queries and timeline analysis.
	•	Basic SIEM hands-on tasks like:
	•	Searching for Indicators of Compromise (IOCs)
	•	Tracking lateral movement
	•	Investigating brute-force login attempts

4. Incident Response Foundations
	•	Understanding the IR lifecycle:
	•	Preparation
	•	Identification
	•	Containment
	•	Eradication
	•	Recovery
	•	Lessons Learned
	•	How SOC teams document incidents and perform root-cause analysis.

5. Threat Intelligence
	•	Understanding IOC types (hash, domain, IP, filename, registry key).
	•	Using OSINT tools to validate threats.
	•	Mapping attacker behavior to MITRE ATT&CK.

6. Malware Indicators & Host-based Detection
	•	Identifying suspicious processes, persistence mechanisms, and registry modifications.
	•	Using basic tools and commands to investigate host compromise.

 Key Practical Skills Gained
	•	Log investigation
	•	Threat detection
	•	SIEM search queries
	•	Interpreting SOC alerts
	•	Event correlation and analysis
	•	Understanding attacker behavior and defensive response
