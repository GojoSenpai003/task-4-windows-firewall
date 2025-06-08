Task 4 – Windows Firewall Configuration (Cyber Security Internship)
Overview
As part of the Cyber Security Internship program, I completed Task 4, which involved configuring basic firewall rules using Windows Defender Firewall. The goal was to understand how firewalls filter traffic, apply inbound rules, and manage network security at the operating system level.

What I Did
Opened Windows Defender Firewall via the Control Panel.

Accessed Advanced Settings to manage Inbound and Outbound rules.

Created a new Inbound Rule to block TCP traffic on port 23 (Telnet), which is often considered insecure.

Tested the rule to ensure port 23 was blocked (Telnet connection failed).

Deleted the rule afterward to restore the system’s default state.

Documented each step as part of the learning process.

Why Port 23?
Port 23 is used by the Telnet protocol, which sends data (including login credentials) in plain text. Blocking this port helps mitigate risks from unauthorized remote access or eavesdropping.

Key Learnings
How Windows Firewall manages inbound and outbound rules.

The difference between allowing and blocking ports.

Importance of blocking insecure services like Telnet.

How firewall rules can be tested and safely removed.

Conclusion
This task helped me gain hands-on experience with configuring and testing firewall rules in Windows. It also improved my understanding of basic network security principles and how firewalls contribute to protecting a system.
