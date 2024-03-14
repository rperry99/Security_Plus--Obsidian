---
Area: "[[Cyber Security]]"
tags:
  - Note
  - NetworkAttacks
aliases:
---
# What is it?
- The [[LAN Switching|MAC address table]] is only so big, and an attacker can start sending traffic with different source [[Media Access Control Address (MAC Address)|MAC addresses]].
	- This forces out the legitimate MAC addresses.
- The table fills up, and the switch begins flooding traffic to all interfaces.
- This effectively turns the switch into a hub
	- All traffic is transmitted to all interfaces
	- There are no interruptions in the traffic flows.
- The attacker can easily capture all network traffic.

# Protecting from flooding
- Flooding can be restricted in the switch's port security settings
	- Often called "Floodguard".


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
