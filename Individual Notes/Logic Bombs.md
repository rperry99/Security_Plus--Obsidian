---
Area: "[[Cyber Security]]"
tags:
  - Note
  - AttackTypes
aliases:
  - logic bomb
---
# What is a logic bomb?
- An attack that occurs when a specific condition is met.
	- _If xx run yy._
	- _At 10pm EST, run..._
- They can trigger via an action or by a date / time.
- These are very difficult to recover from, and hard to find until it goes off.

# Real World Logic Bomb Examples
- March 19th, 2013, South Korea
	- Email with malicious attachment sent to South Korean organizations.
	- Posed as a bank email, and a [[Trojan Horses|trojan]] installs [[Malware]].
	- March 20th, 2013 2pm Local time
		- Malware time-based logic bomb activates.
		- Storage and master boot record deleted, system reboots.
		- Boot device not found
		- Please install an operating system on your hard disk.
- December 17th, 2016 11:53pm
	- Kiev, Ukraine, high voltage substation, logic bomb begins disabling electrical circuits.
	- Malware mapped out of the control network began disabling power at predetermined times.
	- Customized for [[Supervisory Control and Data Acquisition (SCADA)]] networks.

# Preventing a Logic Bomb
- These are difficult to recognize as each one is unique with no pre-defined [[Malware Signatures|signatures]].
- Any unknown or unrecognized changes should come across as suspicious.
- Use electronic monitoring that can alert on changes.
	- Host-Based [[Intrusion Detection System (IDS)|IDS]], Tripwire, Etc.
- Constant Auditing; an admin can circumvent existing systems.


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
