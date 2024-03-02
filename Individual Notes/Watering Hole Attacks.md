---
Area: "[[Cyber Security]]"
tags:
  - Note
  - SocialEngineering
aliases:
  - watering hole attack
  - watering hole
---
# What is it?
- When your company has really good security, attackers can learn websites they use and get information through them, similar to a 3rd party.
- "Go where the victim hangs out".
# Executing the attack
- Find out where the victim goes / what website they use:
	- Food shop websites, industry-related sites, etc.
- Infect one of these third-party sites using a site vulnerability or email attachments.
- Infect _all_ visitors.
	- Even if all visitors are infected, the attacker can choose to ignore most of them, and only get the information from the people they are interested in. 
# Defense against these attacks
- Make sure you use [[Defense In Depth]]
	- Use layered defenses, it's never just one thing
- [[Firewalls]] and [[Intrusion Prevention System (IPS)|IPS]] to stop the traffic before things get bad.
- [[Anti-Virus (AV)]] / [[Anti-Malware]] signature updates
	- Always keep these up to date.

### Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
