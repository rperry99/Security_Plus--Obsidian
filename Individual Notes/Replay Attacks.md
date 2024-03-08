---
Area: "[[Cyber Security]]"
tags:
  - Note
  - ApplicationAttacks
aliases:
---
# What is it?
- A crafty hacker can take advantage of information transmitted over the network. 
- They need access to the raw network data, and to do this, they can use a [[Network Tap]], [[ARP Poisoning]], or [[Malware]] on the victims computer.
- The gathered information may help the attacker replay the data to appear as someone else.
- This is _not_ an [[On-Path Attacks|on-path attack]] as the actual replay doesn't require the original workstation.

# Types of Replay Attacks
- [[Pass The Hash]]
- [[Session Hijacking]]

# Avoiding Replay Attacks
- Use a [[Session IDs|session ID]] with the password hash to create a unique authentication hash each time ([[Salting]])


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
