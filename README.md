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
