---
Area: "[[Cyber Security]]"
tags:
  - Note
  - NetworkAttacks
aliases:
  - MAC address table
---
# What is LAN switching?
- [[Local Area Network (LAN)]]
- The system will forward or drop frames based on the destination of the [[Media Access Control Address (MAC Address)|MAC address]].
- The network gathers a constantly updating list of [[Media Access Control Address (MAC Address)|MAC addresses]], which builds a list based on the source MAC address of incoming traffic.
	- These addresses age out of the list, usually around 5 minutes.
- This also helps maintain a loop-free environment using [[Spanning Tree Protocol (STP)]].

# Adding the MACs to the table
- Switches examine incoming traffic, and make a note of the source [[Media Access Control Address (MAC Address)|MAC address]].
- Switch adds unknown MAC address to the MAC address table
	- Sets the output interface to the received interface.

# Attacks related to LAN Switching / MAC Address Tables
- [[MAC Flooding]]
- [[MAC Cloning]]

---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
